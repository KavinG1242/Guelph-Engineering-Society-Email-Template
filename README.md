# Guelph-Engineering-Society-Email-Template
The University of Guelph Engineering Societies Weekly Newsletter Template
Standard Operating Procedure for Weekly Newsletter Program

This SOP outlines how to use the provided HTML and CSS template to create and send a weekly newsletter via email. Follow the steps below for efficient usage and proper formatting.

1.	Overview
This program provides a structured template for designing visually appealing weekly newsletters. It includes sections for:
•	Announcements
•	Upcoming Events
•	Ongoing Events
•	Footer with social media links

2.	Prerequisites
Before using the template, ensure:
•	You have basic knowledge of HTML and CSS.
•	Access to Visual Studio Code (VS Code) as your code editor.
•	An email marketing tool or service (e.g., Mailchimp, Constant Contact) that supports custom HTML templates.
•	All images and links for the newsletter are prepared.
If images are not sourced from the internet, use ImgBB to host them. Upload your image, open the generated link, and copy the HTML address to use in the src attribute of image tags.

3.	Steps to Use the Program Step 1: Open the Template
1.	Copy the provided HTML and CSS code.
2.	Open Visual Studio Code (VS Code) and create a new file named newsletter.html.
3.	Paste the code into this file and save it.
Step 2: Update Header Section
1.	Locate the <title> tag and update it with the newsletter’s title (e.g., Week 12 Announcements).
 
2.	Replace the logo or banner image in the <img> tag under the .header-section class with your desired image.
o	Update the src attribute with the new image URL or the link hosted on ImgBB.
Step 3: Modify Announcements and Events
1.	Navigate to the Upcoming Events section.
o	Update the event titles, descriptions, dates, times, and locations.
o	Replace the placeholder image URLs (src attributes) with your event-specific images or ImgBB-hosted links.
o	Ensure that all links (<a> tags) redirect correctly to the desired web pages.
2.	Repeat for the Ongoing Events section.
Step 3.1: Adding More Events Adding a New Upcoming Event
1.	Navigate to the Upcoming Events section in the HTML file.
2.	Look for a block of code resembling the following:
   
  	`<div class="announcement">
	<h3>Event Title</h3>
	<p>Description of the event, including date, time, and location.</p>
	<img src="path-to-image.jpg" alt="Event Image">
	<a href="link-to-event-details">Learn more</a>
	</div>`
 
4.	Copy this block of code and paste it directly below the last event in the section.
5.	Update the placeholders (Event Title, Description, path-to-image.jpg, and link-to-event- details) with the details of the new event.
Adding a New Ongoing Event
1.	Navigate to the Ongoing Events section in the HTML file.
2.	Look for a block of code similar to the following:

	`<div class="announcement">
	<h3>Event Title</h3>	
	<p>Description of the ongoing event, including details and duration.</p>
	<img src="path-to-image.jpg" alt="Event Image” 
	<a href="link-to-event-details">Learn more</a>
	</div>`
 
3.	Copy this block of code and paste it below the last ongoing event.
4.	Replace the placeholders with the new ongoing event's details.
   
Step 3.2: Testing After Adding Events
1.	Save the file and open it in a web browser to confirm the new events display correctly.
2.	Ensure all links and images for the newly added events function as expected.
3.	Preview the email to verify the formatting for both desktop and mobile devices.
   
Step 4: Customize Footer
1.	Replace the social media icons’ URLs in the .footer-section with the appropriate links to your platforms.
2.	Update any additional footer content as needed.
   
Step 5: Validate the Template
1.	Use an HTML validator (e.g., W3C Validator) to check for errors.
2.	Open the file in a web browser to preview the newsletter.
3.	Confirm that all text, images, and links are displayed correctly.
   
Step 6: Import to Email Service
1.	Log in to your email marketing tool.
2.	Select the option to create a custom HTML email.
3.	Paste the contents of newsletter.html into the HTML editor.
4.	Preview the email to ensure formatting is intact.
   
Step 7: Send Test Email
1.	Send a test email to yourself or a colleague.
2.	Verify that:
o	The layout appears as expected.
o	All links and images are functional.
o	The email is mobile-friendly.

Step 8: Schedule and Send
1.	Schedule the newsletter to be sent at the desired time.
 
2.	Monitor the email campaign for successful delivery.

4.	Embedding Images
To embed images effectively:
1.	Use direct URLs for images hosted online.
2.	For images not online, use ImgBB:
o	Upload the image to ImgBB.
o	Copy the HTML address from the generated link.
o	Paste this link into the src attribute of the image tag.

5.	Ways to Embed Images
1.	Direct hosting: Use images from public websites by copying their URLs.
2.	Self-hosted: Use your web server to host images and link them via their paths.
3.	ImgBB: Upload images to ImgBB, copy the HTML link, and use it in the src attribute of the image tag. Ensure proper formatting for Outlook and email compatibility.

6.	Sending the Email
1.	Open the newsletter.html file in your web browser.
2.	Select the entire content by pressing Ctrl+A, then copy it using Ctrl+C.
3.	Open your email draft in Outlook.
4.	Paste the content into the draft using Ctrl+V. Ensure that you keep the source formatting intact.
5.	Review the email layout and make any final adjustments as needed.

7.	Tips and Best Practices
1.	Optimize Images: Use compressed images to reduce email size and improve load times.
2.	Responsive Design: Test the newsletter on various devices to ensure it’s mobile-friendly.
3.	Consistency: Maintain a consistent style and tone in all newsletters.
4.	Accessibility: Use alt text for images to make the newsletter accessible to screen readers.
 
5.	Testing: Always test the newsletter before sending it to your audience.

8.	Troubleshooting

Issue	Solution
Images not loading	Check image URLs and ensure they are hosted on a public server or ImgBB.
Broken links	Verify all hyperlinks are correctly formatted and functional.
Formatting issues	Validate the HTML/CSS code and correct any errors.
Email flagged as spam	Avoid spammy keywords and ensure proper sender authentication.

9.	Maintenance
•	Update the template regularly to reflect branding or style changes.
•	Maintain a repository of past newsletters for reference.
•	Periodically review the SOP for improvements or updates.

By following this SOP, you can efficiently create and distribute weekly newsletters, ensuring clear communication and professional presentation.
