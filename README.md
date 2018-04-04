# SRE-Email-Templates
Responsive email templates used by Compassion International

Start with index.html for an email with the standard blue bar header.  If for any reason you need a custom footer for an email, you can start with index-no-footer.html.

For an email that uses a 600 pixel wide header image without the blue bar, start with header-option-2.html.  This file contains the header, content area and footer.

Within index.html, you will see a place to copy in the header code.  The standard blue bar header is header-option-1.html. (More header options will be coded in the future).  You can then add in content rows between the following comments:

	  <!-- =============================================== -->
          <!--		ADD ADDITIONAL CONTENT ROWS BELOW        -->
          <!-- =============================================== -->
		  
          <!-- =============================================== -->
          <!--		ADD ADDITIONAL CONTENT ROWS ABOVE        -->
          <!-- =============================================== -->

All of the content modules are set up as table rows beginning and ending with <tr> tags.  Some content modules also have CSS that will need to be pasted into the head of the document, this can also include CSS that will need to be added to the media queries.

Any images that are used in the templates will need to have the image paths updated to reflect new images that are used for each email or campaign.