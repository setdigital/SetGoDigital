# SGD-Website-Current

Changes made by James
1. Changed the 3 images/ logos under reviews on homepage to be more proportional and consistent.
2. Changed the Nav menu items hover effect from Dark blue to White.
3. Changed font weight of nav menu items and logo in top left to 600 to make it easier to see.
4. Changed the form layout around a little on homepage and contact.
5. Changed "Landed" to "SetGoDigital" for logo in top left for every page.
6. Changed the three main points on homepage about your brand. Go to details for more on this.
7. Added space between review section and content above it.
8. Removed some padding from contact form at bottom of page, was too much of a gap between elements.
9. Changed the content of the three main points on homepage.
10. Changed the hero section content to say Design.Market.Succeed. with subtext of "Tailored
    strategies for your online success.
11.


Changes planned to be made by James
- Change 2/3 images from homepage to be more on brand
- Change content
- Made the width of the form smaller in desktop mode, it is too wide currently
- The three main point titles aren't centered
- The little icons on homepage are not centered in their container




More Details on Changes Made
1. I noticed the three images/ logos under review were uneven, not proportional, and had different background
colors. I went in and made a specific class in the section element: <section class="review-section"> and used
this to target that class more specifically. I was now able to use css to align the containers horizontally,
change the background to white of each container, and individually adjust each logo of each container since
they all are in different dimensions in the filepath. Had to go back and make this change more responsive.

2. Changed the nav menu items from dark blue to white for visibility reasons. Since the website is dark the
dark blue is too hard to see on dark background, I went with white which looks cleaner. There was a weird
effect I noticed when changing the main.css file for a:hover. When chaning the color to white for a:hover,
it worked for all items except Services. It would hover and change to white but right after not hovering,
Services would turn dark blue then back to the normal light grey. I had to do some searching and found that
the below css code was responsible for it, I changed the color to white where it was dark blue.
#header nav ul li.active>a,
#header nav ul li.active>span {
	color: #ffffff;
}

3. Simply added font weight, felt that the items didn't fill the page enough. This should draw more attention to
nav menu.

4. The form was stacked on top of each field. The button was aligned left and there was redundant labels
saying what each field is. I made the button more evenly spaced vertically and centered it horizontally with
the form. I Removed the labels and added placeholder text for users to know where stuff goes. I used flexbox
to space out the form and it's items.

5. Changed the logo from "landed" to "setgodigital" in top left.

6. For every point I removed the subtext that was below the h2 title. For instance, where it said "Our Process"
underneath it, I removed the sentence since it was repetitive. I also changed the third point to saying
"Your Vision, Our Commitment" I feel like this is more meaningful.

7. The review section and the content above it was colliding and too close, I gave it 120px space between vertically.

8.

9. I felt like the three main points should build off one another and be more on brand. I decided on "Empowering Your
Digitital Presence", "Our Process", and "Your Vision, Our Commitment". I feel like these three main points quickly
and effectively sum up what your brand is about. I also went ahead and centered the titles of the main points.

10.