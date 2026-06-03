---
layout: school_project
title: SLF Functional Prototype
description: Prototyping Description
image: /assets/images/slf/slf.jpg
---

<div class="info-box" style="border-left-color: #0077cc; background:#f2f7ff;">
  <h3 style="color: black;">Project Outline</h3>
  <p style="color: black;">In our Intro to Mechanical Design class, we were tasked with developing an initial proof of concept and functional prototype to test various characteristics of our proposed design for treating SLFs.</p>
</div>

## First Prototype Testing Summary

![First Prototype]({{ "/assets/images/slf/prototype.png" | relative_url }}){: style="width:100%; display:block;" }
- Above is the physical mock-up we made of our device. The left side with the broom head is the scraper side (the head is only on there since it was impossible to remove without breaking the broom).
- The dustpan and cardboard structure are a decent representative of the scraper system. The handle has a forearm brace that supports the forearm below for the lift of the pole and above for the scraping action. 
- From testing the relative geometry and weight of the design, we decided that a brace behind the handle would be best. It should have a flexible loop that supports during lifting and then a more rigid, arc-shaped part that molds to the forearm and helps brace the tool while actually scraping. In terms of ergonomics, a rounded grip would be nice (we used the handle from a hot glue gun) and can be 3D printed or shaped on a lathe.
- Our physical mockup had about 5 pounds of weight on the end (broom head) and was about 4 feet long. This was pretty easy to handle, which means that as long as our geometry doesn't create a moment more than around 20 pound-feet, it should be okay in terms of ease of use. In reality, we will probably have the device be slightly longer with much less weight at the end, leading to less of a moment.
- Since the handle and rod setup were tested here, the functional prototype is focused solely on the scraper itself (the part we haven't tested). Essentially, our findings from our first prototype led us to create a relatively simple prototype for the functional prototype, as seen in the documentation below.

## Functional Prototype Testing Summary
### Documentation
Parts Used:
- 1.158" diameter Wooden Rod found in lab
- Custom 3D-printed scraper

Design Intent Sketches/CAD:
![Renderings]({{ "/assets/images/slf/renderings.png" | relative_url }}){: style="width:100%; display:block;" }

Scraper Specs:
- Bottom length: 10" (from edge of the scraper to bottom end of hole)
- Height: 5.5" (from bottom plane to top of arch)
- Width: 6"
- Length of cylinder (for press-fit): 2.5"

Instructions for Assembly:
- We sanded down the wooden rod slightly to better press-fit it into the scraper's cylindrical hole
- The press-fit was the best technique for prototype purposes and could probably be used again for the final design, but we will likely add a notch to securely prevent rotation of the two parts

### Design Tests:
**Scraping Efficacy**
- Tests: Scraper ability to collect egg masses
- Procedure: Put 10 different-shaped egg masses (clay blobs) on the wall and scrape them from different angles (between horizontal and vertical) to simulate scraping egg masses in real life. The heights of the egg masses varied from 126 cm above ground to 200 cm above ground: one was placed about 30 cm from ground for variety (specifically: 29, 126, 143, 145.5, 150, 152, 178, 196, 198, and 200 cm above ground). We scraped each egg mass 1-3 times or until approximately 90% of the clay was gone. The images below show our setup and some highlights of the results.
![Scraping 1]({{ "/assets/images/slf/scraping1.jpeg" | relative_url }}){: style="width:40%; display:inline-block;" }
![Scraping 2]({{ "/assets/images/slf/scraping2.jpeg" | relative_url }}){: style="width:40%; display:inline-block;" }
![Storing]({{ "/assets/images/slf/holding.jpeg" | relative_url }}){: style="width:40%; display:block;" }
- Test results: Overall, the scraper was effective. It was able to scrape more than 90% of the clay for 9/10 of the "egg masses". The single point of failure occurred at a negative-clearance corner geometry, indicating a required design modification for the scraper's geometric profile. It is also important to note that these simulated egg masses were heavier and stickier than a real SLF egg mass is.
Conclusions: Our current scraper geometry is effective on smooth surfaces; it has issues with corners, and we noticed that the scraper's flared walls make it so that you can only scrape if the scraper is almost flush with the wall. We will probably remove this flare and possibly add a modular attachment/side of our scraper for less even geometry, like corners.

**Scraper Size**
- Tests: Is the scraper big enough?
- Procedure: During the efficacy trials, we conducted a visual audit of the debris capture rate. 
- Conclusions: This means that the scraper geometry we have has thick enough walls and is strong enough for our purposes.

**Success Criteria**
Context: Our project is a scraper designed to remove spotted lanternfly egg masses from surfaces such as walls, trees, and other outdoor structures while collecting the removed material. The egg masses are about 0.5g and 1.5in long. Our product is specifically excellent targeting masses located out of normal reach. Our functional prototype is a high-reach, pole-mounted mechanical scraper designed to replace manual scraping methods.

1. Scraping efficiency
    - The scraper should remove at least 90% of a simulated egg mass within 3 scraping motions.
    - This assesses the functional ability of the blade's geometry to detach masses from uneven/textured surfaces. 
    - Testing can be done by placing 10 clay masses at varying heights on multiple surfaces and scraping them using the prototype. After scraping, visually analyze the remaining clay. At least 8 out of 10 egg masses must have >90% removal within three scrapes.
    - This is our highest priority criterion and can be exemplified in an exhibit day demo of the procedure described above.
2. Blade Durability
    - The scraper blade must lose <5mm of material length after 40 aggressive scraping cycles.
    - This assesses the lifespan of the scraping edge of our prototype.
    - To test this we will measure the initial length of the scraper blade using digital calipers, perform 40 scraping cycles on sandpaper, and take a final measurement to calculate material loss.
3. Total Weight
    - The total weight of the fully assembled tool (head, pole, handle, and fasteners) must not exceed 10 pounds.
    - This is assessing user fatigue and ergonomic viability, as holding a heavy tool at the end of a long moment arm is physically taxing. 
    - To test this, the fully assembled prototype will be weighed on a digital scale.
4. Operational Reach
    - The scraper must achieve a >90% mass removal rate on targets placed between 8 and 10 feet tall.
    - This is testing the tool's ability to transmit sufficient normal force (pushing into the wall) and shear force (scraping up) at extreme operating angles, without requiring the user to change their grip or use a ladder.
    - We will test this using the scraping efficiency test listed above but with the clay masses placed at the maximum reach height of the device.



