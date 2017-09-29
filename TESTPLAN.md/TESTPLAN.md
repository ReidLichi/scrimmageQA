## Merchant Portal

### Account creation
    Ensure that an admin is able to successfully create an account.

Validate:
- [ ] Admin is able to create a new merchant account from the Merchant Portal.
- [ ] Required fields are indicated.
- [ ] Legacy ID field type is "numeric" and required.
- [ ] Home Page URL field type is "URL" and requires a valid address.
- [ ] Password field type is password.
- [ ] Admin can successfully create an account. All fields have been entered correctly.

### Group Dashboard
    Ensure that a user is able to successfully create a group.
Validate:
- [ ] Able to upload a logo:
  * PNG
  * GIF
  * JPG
  * TIFF
- [ ] Create a new Group
- [ ] Create a new Version

### Create A New Version
    Ensure that a user is able to successfully create a version in a group.
Validate:
- [ ] Title is "AlphaNumeric" and required
- [ ] Description is "AlphaNumeric" and required
- [ ] Contact Email is "Email" and requires a valid email address
- [ ] Website URL is "URL" and requires a valid address
- [ ] Contact Us URL is "URL" and requires a valid address
- [ ] Admin can successfully create a version. All fields have been entered correctly.

## Version Control Center

### General Catalog Settings
    Ensure that a user is able to configure the general version settings
Verify:
- [ ] Tracking codes update in the Dynalog
- [ ] Language updates in the Dynalog
- [ ] Currency updates pricing symbol in the Dynalog
- [ ] Carousel text location updates in the Dynalog
- [ ] Category Menu Label updates both Mobile and Desktop in the Dynalog
- [ ] Category Menu Shows Groups updates in the Dynalog
- [ ] Validate the following Desktop Options:
  * Verbiage on toggleable options is consistent.
  * Toggle Logo in Light-box
  * Iframe Product Linkouts
  * Quickview button for Light-box
  * Product Image Hover options
  * Search Box Options (show/hide)
  * Left Navigation Bar Covers
  * Carousel (show/hide)
  * Carousel "Show All" option (show/hide)
  * Allow SMS Text Message Option
  * Cover call to Action
- [ ] Validate the following Mobile Options:
  * Verbiage on toggleable options is consistent.
  * Product Linkout Options
  * Product Titles on products
  * Mobile Lifesyle Images (show/hide)
  * PDF Slide Sideways
  * Search Box (show/hide)
  * Cover shows in the left navigation of other Dynalogs
  * Carousel "Show All" option (show/hide)
  * Pass mobile navigation info on product URLs
  * Flashing "Press Here" after pausing flip action



### Manage Lead Options
    Ensure that a user is able to configure the Lead Options for a version.
Verify:
- [ ] Lead Form Options work in the Dynalog.
- [ ] Desktop Options work in the Dynalog
- [ ] Mobile Options work in the Dynalog
- [ ] Message updates in the Dynalog
- [ ] Additional message updates in the Dynalog
- [ ] Submit Button Label updates in the Dynalog
- [ ] Notification Email is received when form is filled.
- [ ] Request phone is updated
- [ ] Comments are updated in the Dynalog
- [ ] Manage Lead Form Options are successfully updated in the Dynalog
- [ ] Export your leads

### Manage Auto Play Options
    Ensure that the Manage Auto Play Options can be configured
Verify:
- [ ] URL Target can be updated in the Auto-Play URL
- [ ] Flip Interval is correctly timed in the Auto-Play URL
- [ ] Banner Message is updated in the Auto-Play URL
- [ ] Page Ranges are correctly displayed in the Auto-Play URL
- [ ] Open URL Target window correctly opens (new tab or same window)
- [ ] Left Navigation Bar displays properly (show/hide)
- [ ] Manage Auto Play Options are successfully updating in the Auto-Play URL

### Uploading Feeds
    Ensure that a user can successfully upload a feed
Verify:
- [ ] The following feed types can be uploaded:
  * CSV
  * TSV
  * XML
- [ ] Upload a new feed to create a new version
- [ ] Overwrite Existing feed
- [ ] Auto Process Feed Without Customization
- [ ] Map the feed and verify that the 5 mandatory fields are required.

### Processing Feeds
    Ensure that a user can sucessfully process a feed
Verify:
- [ ] Products can be assigned from:
  * Nothing (The feed is a new version and no cloning)
  * From Old Version (cloning from a previous version)
  * From Feed (The "Featured" list is mapped)
  * Random/300 (Group Setting is turned on)
- [ ] Amazon Servers can be Started / Stopped / Flushed
- [ ] Send a feed to be processed on the following servers:
  * Images1
  * Images2
  * Amazon1
  * Amazon2
  * Amazon3
  * Amazon4
  * AmazonTiny
- [ ] Process types:
  * Regular Processing
  * Search Dynalog
  * Re-Process Images
  * Process Outstanding Images
  * Simulate Processing
- [ ] Process a feed with different Image Qualities (did anything change?)

### FTP Feed
    Ensure that a user can setup FTP feeds
Verify:
- [ ] Generate Password sets up a new password
- [ ] Use an FTP client like Filezilla to access that user using the new password.
- [ ] Upload a file to the FTP to test
- [ ] Feed type matches the uploaded file on the FTP
- [ ] What happens when a feed type does not match the uploaded file on the FTP
- [ ] Change the Processing Mode
- [ ] "Keep all pages same" test both options
- [ ] "FTP processing is active" setting updated

### Augment Feed Data
    Ensure that a user can augment an existing feed
Verify:
- [ ] Upload a feed that matches the feed type
- [ ] Does the system Validate the feed matches the feed type chosen?
- [ ] Process Augmented Feed Data
- [ ] Do new products get processed?
- [ ] Are existing product titles, descriptions, prices, URLs, and Images processed?
- [ ] Download original feed

## Manage 3.0 Catalog

### Assign Products
Verify:
- [ ] You can assign up to the limit of featured products (default 300)
- [ ] You can Clear All products from the featured list
- [ ] You can sort by Category
- [ ] You can limit the number of products displayed in the results view
- [ ] You can move to the next list of results to be displayed
- [ ] View the list of featured products
- [ ] Re-order the featured products
- [ ] Un-feature the assigned products

### Manage Pages
Verify:
- [ ] You can navigate to different pages of the Dynalog
- [ ] You can move products to and from the bucket
- [ ] Page Options:
  * Products per page / Apply to All Pages / Revert Random Count
  * Page Layout:
    * Choose Layout: Square / Vertical /Horizontal
    * Apply to pages: This page / All pages
  * Select New Background:
    * Color
    * Patterns
    * Repeat Backgrounds
    * Apply to pages: All Pages / This Page / This Spread
  * Toggle Logo Visibility
  * Border Options:
    * Show / Hide
    * Apply to pages: This page / All pages
  * Price Options:
    * Price on pages
    * Prices on Quick View
    * Apply to pages: This page / All pages
  * Lifestyle Image:
    * Upload Lifestyle Image
    * Page Linkout Details
    * Page URL
    * Hover Text
    * Price
    * Convert to Category Style Page
  * Category Style Page
- [ ] All Manage Pages Options work in the Dynalog

### Manage Products
- [ ] Search for a product and:
  * Modify the data
  * Modify the image
  * Was the product featured, did it change the order of the managed pages?
- [ ] Add New Product
  * Did the system validate required fields?
  * Verify if product was added

### Manage Search Options
- [ ] Display multiple products in the Related Products window by (defaulted to Description)
- [ ] Sort Related Products by:
- [ ] All Search options work in the Dynalog

### Manage Categories
- [ ] Enable Desktop Categories
- [ ] Enable Mobile Categories
- [ ] Enable Category Dynalogs by:
  * Product Listing
  * Mini Dynalogs
- [ ] Default Category Processing:
  * Products Per Page
  * Image Orientation
  * Hide Subcategories if Main Category has less than...
- [ ] Mass Update
- [ ] Activate categories and preview
- [ ] Set cover image for Categories

### Manage PDF Catalog
- [ ] Upload a PDF
  * Did the system validate the dimensions?
  * What happens if you process a PDF with different page sizes
- [ ] Process PDF Page Dimensions:
  * Width / Height
  * Image Quality
  * Custom Width / Height
- [ ] Copy from Master PDF
  * Clone Features
  * Match Annotation Field
- [ ] Annotate PDF
  * Use same SKU multiple times
  * Does the annotation appear in the same place on the live Dynalog?
- [ ] Page Options
  * Is Double Spread
  * Page Linkout: Top / Bottom
  * Is Request Form

### Live Dynalog
Verify:
- [ ] Pages Flip
- [ ] Quickview opens and shows related products
- [ ] Details button linksout to URL
- [ ] Menu Options all work
- [ ] Search Option displays correctly
- [ ] Categories show products
- [ ] Print Page
- [ ] Text to phone
- [ ] Share on social media

