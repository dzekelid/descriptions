swagger: "2.0"
x-collection-name: eBay
x-complete: 1
info:
  title: Ebay
  description: the-ebay-platform-offers-an-unprecedented-opportunity-to-build-a-new-ebay-business-or-expand-your-current-business-reach-new-customers-and-create-a-potential-new-stream-of-revenue--leverage-the-resources-of-the-ebay-developers-program-to-tap-into-the-ebay-marketplace-with-millions-of-active-users-globally-with-tools-and-services-that-meet-the-diverse-needs-of-buyers-and-sellers-
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /item_description:
    get:
      summary: Get Item Description
      description: 'The Description feed file is generated each day. This call lets
        you download a daily TSV_GZIP (tab separated value gzip) Description feed
        file containing the descriptions of all the items that were listed on a specific
        day in a specific category. To store the complete item details, you would
        always run the getItemFeed and getItemDescriptionFeed calls with the same
        parameters. &nbsp;&nbsp;&nbsp; /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
        &nbsp;&nbsp;&nbsp; /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
        Combining the Description and Item feed files The Description feed file contains
        only the itemId, itemGroupId and description columns. The value of the description
        column is BASE64 encoded. For each row, there will be values in either itemId
        or itemGroupId. The description column will always contain a value. itemGroupId
        - The value in this column is the ID of an item group (an item with variations,
        such as size and color) where the items in the group share the same description.
        Even though the itemGroupId represents more than one item, the itemGroupId
        and description are returned only once for the entire group. In this case,
        there will be values in the itemGroupId and description columns. You match
        the value of itemGroupId from the Description feed file with the value of
        primaryItemGroupId from the Item feed file for the same day and category.
        itemId - The value in this column is the ID of an item that is not part of
        an item group or (in rare cases) the item is part of an item group but does
        not share a description with other items in the group. In this case, there
        will be values in the itemId and description columns. You match the value
        of itemId from the Description feed file with the value of itemId from the
        Item feed file for the same day and category. The file will contain the descriptions
        for all the items or item groups from all the child categories of the category.
        The first line of the file is the header, which indicates the order of the
        values on each line. Each column is described in the Response fields section
        on this page. Downloading feed files Description feed files are very large
        so the gzip file, which is binary, is streamed in chunks. You specify the
        size of the chunks in bytes using the Range request header. The Content-range
        response header indicates where in the full resource this partial chunk of
        data belongs and the total number of bytes in the file. For more information
        about using these headers, see Retrieving a gzip feed file. Important: The
        response is always a TSV_GZIP file. But for documentation purposes, the response
        is shown as JSON fields so that the value returned in each column can be explained.
        The order of the response fields, shows you the order of the columns in the
        feed file. Restrictions For a list of supported sites and other restrictions,
        see API Restrictions.'
      operationId: getItemDescriptionFeed
      x-api-path-slug: item-description-get
      parameters:
      - in: query
        name: category_id
        description: An eBay top-level category ID of the items to be returned in
          the feed file
      - in: query
        name: date
        description: The date of the feed file you want
      - in: query
        name: feed_scope
        description: Controls the contents of the feed file
      - in: header
        name: Range
        description: This header specifies the range in bytes of the chunks of the
          gzip file being returned
      - in: header
        name: X-EBAY-C-MARKETPLACE-ID
        description: The ID for the eBay marketplace where the items are hosted
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Item
      - Description