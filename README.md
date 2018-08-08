## App Name 

Matamata Country Lodge - Bootstrap v4 web app

##### Synopsis / Summary 

Matamata Country Lodge (retirement village) required a website to help them promote their facility. In particular, the client wanted to showcase their award winning landscaping and gardens and the fact they are an NZ family owned and operated business - a relatively unique selling point in the industry!

###### Staging URL

https://toddmoody.github.io/mcl-bootstrap/

###### Key functionality / deliverables

- UI/UX design
- Front-End development (incl CSS grid image gallery)
- Deployment & Hosting
- SEO (in progress)
- Ad-Words / PPC promotion

###### Technology 

- NPM
- Sketch & Photoshop (UI/UX)
- Final Cut Pro (creation of moving content from still images)
- HTML
- Bootstrap v4
- SCSS incl Flexbox & CSS Grid
- Gulp 

###### More on technical process

I really wanted to focus on usability and ease of navigation with this build and essentially cater to a very broad range of users and age groups (elderly residents but also their families that often research on their behalf). I decided to utilise Bootstrap v4 in this case largely due to how robust it is responsively and I also wanted to utilise a couple of their pre-built components incl. the navigation and alert bar. I also utilised a base theme due to client budget constraints - largely to cut down on initial set-up and config time.

I really wanted to improve the overall usability and it was known that many of the child pages on the previous site (which was a WordPress site) were visited very infrequently (due to a fairly clunky navigation and lack of links outside of the main navigation bar).

It had been a while since I'd used the Bootstrap framework in detail so it was a good opportunity to dive into v4 and I was excited to adopt some of the key components, including:

- The alert component: I've recently seen these collapsable alert bars quite a lot and they formed a key part of the overall page design and really served two key purposes; allowing us to carry the accent color throughout the site, and; allowing us to hero unique page-level messages i.e. "new 2-bed chalets now available".
- The navbar: I think the bootstrap nav is one of the best out there and after coding a few responsive navbars from scratch recently I certainly value the ability to get up and running quickly (especially on projects with limited budget such as this one). I guess the drawback can be the end result looking very "Bootstrap" but in this case I was really happy with the level of customisation and unique on-brand, and highly user friendly end result.

Outside of Bootstrap specifically, the other main objective of this website was to hero the landscaping and gardens and our best assets to achieve this was a library of professional images. I used CSS grid to create a mosaic style gallery which I think worked really well in this case - in particular because I wanted to avoid lightboxes and display large format pics effectively.

In addition to images I also wanted to hero the grounds using some moving content (problem being there was none available).

###### Ideas for enhancement 

- [ ] I've suggested to the client some moving content would be a great asset (i.e. aerial drone type footage of the facility which could be used in the main banner). Additional moving content like resident and family testimonials would also be ideal to supplement the existing static content.
- [ ] Integration with a back-end form service to capture inquires that are submitted would be a cleaner solution (currently using formspree which works to deploy emails to the client but is basic and has no database).
- [ ] Potentially look at improving accessibility for the elderly. A couple of ideas are some JS integration to enlarge the text for readability and maybe work on the overall contrast / colour pallette.
