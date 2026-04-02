---
layout: project
title: Open Design Project
description: Keeping grapes safe from spotted lantern flies
technologies: [Mechanical Design]
image: /assets/images/odp-functional-prototype-page-1.png
show_header_image: false
---

<div class="project-jump-box">
  <p><strong>Linked Table of Contents</strong></p>
  <ul class="project-jump-outline">
    <li>
      <a href="#client-pitch">Client Pitch</a>
      <ul>
        <li><a href="#proposed-statement">Proposed statement</a></li>
        <li><a href="#why-it-matters">Why it matters</a></li>
        <li><a href="#proposed-directions">Proposed Directions</a></li>
        <li><a href="#concept-a">Concept A : Light trap</a></li>
        <li><a href="#questions">Questions</a></li>
        <li><a href="#references">References</a></li>
      </ul>
    </li>

    <li>
      <a href="#functional-prototype">Functional Prototype</a>
      <ul>
        <li><a href="#part-descriptions">Part descriptions</a></li>
        <li><a href="#assembly-instructions">Assembly instructions</a></li>
        <li><a href="#critical-dimensions">Critical dimensions</a></li>
        <li><a href="#design-documentation">Design Documentation</a></li>
        <li>
          <a href="#design-testing">Design Testing</a>
          <ul>
            <li><a href="#light-test">Light test</a></li>
            <li><a href="#shake-test">Shake Test</a></li>
            <li><a href="#speed-test">Speed Test</a></li>
            <li><a href="#throw-tests">Throw Tests</a></li>
            <li><a href="#high-volume-test">High Volume Test</a></li>
            <li><a href="#tolerance-test">Tolerance Test</a></li>
          </ul>
        </li>
        <li><a href="#success-criteria">Success Criteria</a></li>
        <li><a href="#demo">Demo</a></li>
      </ul>
    </li>
  </ul>
</div>

<p class="odp-intro">
As a class, we were tasked to create solutions to help the grape industry be less harmed by the rise of spotted lantern flies (SLFs). Currently, SLFs are an issue, as they get caught in the grape harvest byproduct, causing batches of grapes to be thrown away, which significantly hurts profits and the economic viability of growing grapes.
</p>

<div class="odp-page" markdown="1">

<hr class="section-divider" />

<h2 id="client-pitch">Client Pitch</h2>

<h3 id="proposed-statement">Proposed statement</h3>

**Team:** Grape Guardians.

**Clients:** Cornell CALS Extension / E\&J Gallo Winery / National Grape

The problem we are trying to address is that SLFs tend to land on grapes during their life cycle. This is backed by the fact that there’s an average of 9.3 SLF per vine when looking at vineyards in areas infested with SLFs [1]. Additionally, a 2025 study estimates that in three years, there will be an 8% decrease in yield and a 10% decrease in price of grapes due to a drop in quality [2]. Both of these statistics are major issues, as there are no current ways to separate SLFs from harvested grapes, so we want to prevent the SLFs from getting to the vines in the first place.

<hr class="subsection-divider" />

<h3 id="why-it-matters">Why it matters:</h3>

- Crucial to limit impacts of SLFs on the grape industry - SLFs harm profit and economic viability
- SLFs live longer when eating grapes - preventing access could help to inhibit the spread of SLFs.

<hr class="subsection-divider" />

<h3 id="proposed-directions">Proposed Directions:</h3>

<h3 id="concept-a">Concept A : Light trap</h3>

**Description and Use :** Place large lights at the edges of grape fields to attract SLFs. On the light, there would be a one way trap to prevent the SLFs from leaving.

**Why it’s better than the status quo:**
- **Reduces chemical use**: Unlike insecticide spraying, the light trap doesn’t use chemicals, protecting grape quality, beneficial insects, and the surrounding environment.
- **Draws SLF away from vines**: By Attracting SLF to perimeter lights, it protects grape plants directly.

**End-of-semester proof-of-concept:** A prototype showing the full function of the trapping mechanism.

**Risks:**
- SLFs may be able to leave the trap or avoid entering it. (could be tested in controlled conditions)
- Lights may not be effective during daylight. (test for SLF capture count during the day vs night)
- Enough SLFs don’t go to the lights and the issue persists.

<hr class="subsection-divider" />

<h3 id="questions">Questions:</h3>

1. **What kinds of lights attract SLFs the best (i.e. the most effective lumen or wavelength range)?**
   
   *Decision affected:* Affects the kind of light we would use for the light trap.

2. **Do SLFs tend to only fly near light sources or land on them directly?**
   
   *Decision affected:* Affects the range of our trap.

3. **Are there other insects (the kinds attracted to light) that need to access the grapevines for them to grow properly?**
   
   *Decision affected:* Affects how much we focus on allowing insects that aren't SLFs to escape the trap.

<hr class="subsection-divider" />

<h2 id="references">References</h2>

- [Source [1]](https://link.springer.com/article/10.1007/s10340-020-01233-7#Sec9)
- [Source [2]](https://doi.org/10.1093/jipm/pmae039)

<hr class="section-divider" />

<h2 id="functional-prototype">Functional Prototype</h2>

Due to the length constraints of our client pitch, we were only able to propose one of our two project ideas. But, after we had already sent our proposal, my team decided our second idea would be better to pursue due to its uniqueness and interesting mechanisms. What we decided to make was a trap that consists of a main containment area and a spinning top that forces SLFs sitting on top into it. As SLFs are drawn to light, the spinning disk would be transparent, allowing light from below to shine through and lure the SLFs in. Below is documentation of the fabrication, functionality, and testing of the main mechanism of our device -- the spinning top.

<img src="{{ '/assets/images/ODPdrawing.png' | relative_url }}" alt="Functional Prototype exploded CAD view_" class="center-image odp-hero-image" />

<hr class="subsection-divider" />

<h3 id="part-descriptions">Part descriptions:</h3>

<div class="responsive-table">
<table>
  <thead>
    <tr>
      <th>Part</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Acrylic Plate</td>
      <td>Rotating disk that moves the ridges such that SLFs are put into scenarios where they must go down the tube, or be squished</td>
    </tr>
    <tr>
      <td>Roof</td>
      <td>Prevents SLFs from jumping off the acrylic plate once their set of ridges begins to force the SLFs down the tube</td>
    </tr>
    <tr>
      <td>Ridges</td>
      <td>Match up with ridges built into the roof and force SLFs down the tube, or squish SLFs that don’t go down the tube. Prevents SLFs from getting away.</td>
    </tr>
    <tr>
      <td>Tube</td>
      <td>The component through which SLFs are forced down. Bottom opens into a containment zone where SLFs are imprisoned.</td>
    </tr>
    <tr>
      <td>Nuts &amp; Bolts</td>
      <td>Used at the edges of the acrylic plate. String tied to one and wrapped around the rest multiple times → when the string is pulled, the plate spins.</td>
    </tr>
  </tbody>
</table>
</div>

<hr class="subsection-divider" />

<h3 id="assembly-instructions">Assembly instructions</h3>

combine components as shown in blue above (in exploded view); the only critical order of steps is that the acrylic plate must go down onto the tube before the roof is super-glued on (all other steps can happen in any order).

<hr class="subsection-divider" />

<h3 id="critical-dimensions">Critical dimensions</h3>

diameter of Acrylic plate = 9”; thickness of disk = 1/16”; height from disk to roof = 1”; height of ridges = 0.875”; Dimensions of tube opening = 1” x 1”

<hr class="subsection-divider" />

<h3 id="design-documentation">Design Documentation:</h3>

<div class="responsive-table">
<table>
  <thead>
    <tr>
      <th>Part Name</th>
      <th>Specs</th>
      <th>McMaster Code</th>
      <th>Fabrication</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ridges #1-9</td>
      <td>0.875” tall, widths vary from .25”-1.25”</td>
      <td>N/A</td>
      <td>3d printed out of PLA and done at the RPL</td>
    </tr>
    <tr>
      <td>Roof</td>
      <td>r = 4.5”, matching ridges 3d printed with roof as one piece</td>
      <td>N/A</td>
      <td>3d printed out of PLA and done at the RPL</td>
    </tr>
    <tr>
      <td>Tube</td>
      <td>1.5” diameter</td>
      <td>N/A</td>
      <td>3d printed out of PLA and done at the RPL</td>
    </tr>
    <tr>
      <td>Clear Scratch- and UV-Resistant Cast Acrylic Sheet</td>
      <td>12&quot; x 12&quot; x 1/16&quot;</td>
      <td>8560K171</td>
      <td>Laser cut at RPL</td>
    </tr>
    <tr>
      <td>Bolts</td>
      <td>M4 12mm long from Taylor Design Studio</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Nuts</td>
      <td>M4 from TDS</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
  </tbody>
</table>
</div>

<hr class="subsection-divider" />

<h3 id="design-testing">Design Testing:</h3>

<div class="odp-test" id="light-test">
<h4>Light test</h4>
<p>Does a sufficient percentage of light get through the clear acrylic compared to the amount inside? (ideally, at least 80% of light intensity passes through the acrylic so that the blocked light doesn’t pose the risk of overheating the system)</p>
<p><strong>Procedure:</strong> In a dark room, use a phone flashlight and another phone with a lumen reading phone app 5” apart. Repeat with the clear acrylic sheet in between while remaining 5” apart. Compare the values to identify the percentage of light that passes through.</p>
<p><strong>Part Focus:</strong> Light and clear acrylic top</p>
<p><strong>Results:</strong> We measured 740 lux coming from the phone without acrylic and 610 lux coming from the phone through the acrylic. This means that 83% of the light made it through the acrylic.</p>
<p><strong>Conclusion:</strong> A sufficient proportion of light is escaping through the acrylic. No material change (in terms of thickness or composition) is needed for our next prototype.</p>
</div>

<div class="odp-test" id="shake-test">
<h4>Shake Test (Stability and Support)</h4>
<p>Does the trap maintain integrity during shaky conditions as might be expected on a windy day?</p>
<p><strong>Procedure:</strong> Place the prototype in a desired location and shake it for 10s at 5 Hz (5 shakes per second), seeing if it continues to work during and after being shaken.</p>
<p><strong>Part Focus:</strong> Entire prototype</p>
<p><strong>Results:</strong> We shook it and it did not fall apart. However, the nuts on the four corners of the device used to support our spinning mechanism string came loose</p>
<p><strong>Conclusion:</strong> The device is robust, but for our next prototype, we should use nylon insert nuts to ensure longevity under vibrational conditions.</p>
</div>

<div class="odp-test" id="speed-test">
<h4>Speed Test (Assembly and Fastening)</h4>
<p>Does our spinning top hold up when rotating at higher operating speeds?</p>
<p><strong>Procedure:</strong> Spin the top as fast as possible. No part of the mechanism should break, and the top should still spin smoothly.</p>
<p><strong>Part Focus:</strong> The spinning top</p>
<p><strong>Results:</strong> No parts of the mechanism broke. We were able to spin it at upwards of 7.25 rad/s with no issue (spun 3 rotations in 2.6s). However, we did notice slight friction between the ridges on the disc and the roof. It did not appear to affect the rotation speeds – rotation speed remained constant through the friction occurring.</p>
<p><strong>Conclusion:</strong> The device structure is robust and can operate at high speeds. However, we need to come up with a way of spinning it so we can get more consistent speeds (pulling a string is a bit inconsistent). Additionally, ensuring that ridges are vertical will eliminate any friction between them as they rotate.</p>
</div>

<div class="odp-test" id="throw-tests">
<h4>Throw Tests (Load-bearing Performance)</h4>
<p>Will our device hold up when bugs land on it at high speeds?</p>
<p><strong>Procedure:</strong> Fabricate or find a small object of the approximate mass of a lantern fly (0.5~1 inch). Toss it at varying degrees of speeds at the top of the device while spinning (~3m/s to match the jumping speed of SLFs). Neither the roof nor the spinning top plate should break. In addition, the bug should get “squished” by the rotation, though this criterion might not be met until our final prototype. We will try to get an object that isn’t rigid.</p>
<p><strong>Part Focus:</strong> The ridges on the top of the device</p>
<p><strong>Results:</strong> We threw a mix of 6 (0.5-inch) and 6 (1-inch) bug models at the top spinning device, and not only did it not break, it “caught” all bugs that landed. Additionally, the roof also remained sturdy under “landing impact” without issues.</p>
<p><strong>Conclusion:</strong> The robust top against landing impact and spinning mechanism works well in either trapping the LSF or squashing it. This type of structure works well; no change needed here.</p>
</div>

<div class="odp-test" id="high-volume-test">
<h4>High Volume Test (Load Bearing and Performance)</h4>
<p>Can the trap handle more than one bug going down the shaft at one time?</p>
<p><strong>Procedure:</strong> Try putting multiple lanternfly-shaped objects into the shaft hole at the same time. We approximate that 3-6 “bugs” will be able to fall through.</p>
<p><strong>Part Focus:</strong> Bug shaft</p>
<p><strong>Results:</strong> The 1 in bug models we made were too big to fit through the shaft. However, our 0.5 in models were able to be shaken out of the device. We were able to fit upwards of 6 0.5 in bugs into the assembly and still shake all of them out.</p>
<p><strong>Conclusion:</strong> Due to the entrance to our tube being too similarly sized to a large SLF, they struggled to go down the tube when clumped. Therefore, for our next prototype, we would like to slightly increase the width of the opening (by approximately .25”).</p>
</div>

<div class="odp-test" id="tolerance-test">
<h4>Tolerance Test (Assembly and Fastening)</h4>
<p>Do our tolerances for the slotted ridges work out?</p>
<p><strong>Procedure:</strong> Assemble the prototype. The ridges on the top should fit in tightly and not fall off.</p>
<p><strong>Part Focus:</strong> Ridges</p>
<p><strong>Results:</strong> Everything fit together. However, we had to use a little bit more superglue than we wanted to attach the ridges.</p>
<p><strong>Conclusion:</strong> We concluded that we need a slightly more snug fit – 0.01” as measured by a caliper – to ensure that minimal glue is used. We will apply this to the next prototype.</p>
</div>

<hr class="subsection-divider" />

<h3 id="success-criteria">Success Criteria:</h3>

Our project is a bug catcher that uses light during the evening to lure lanternflies into a spinning trap. The top consists of ridges that force the bug to either move to the center of the trap or be squished.

It should:
- Successfully allow the bug container at the bottom of the trap to be emptied out AND the container should hold at least 1000 SLFs.
  - The bugs need to be emptied out from the trap for it to have a long lifespan and to capture more bugs than its volume would otherwise allow.
  - If the container can’t hold a significant amount of SLFs, it will need to be continuously emptied (unwanted labor burden)
- Allow more than 50% of the light from a given light source to pass through the clear top (measured using a smartphone light intensity meter)
  - Light needs to penetrate the trap in order to attract the bugs
- Successfully transport at least 6 SLF at one time from the top of the shaft to the bug-catching area (6 SLFs can fit between each section of ridges, so this is the maximum the tube will need to handle at once)
  - If multiple bugs land on the trap at once, all of the bugs should be able to be trapped
- Successfully squish a bug-shaped object that is on the plate while it rotates (result is binary: either it works (1) or it doesn't (0))
  - The bugs need to be either killed or forced to the center of the trap to work, so the ridges must establish the threat of death (to force the bugs into the tube or kill them as a backup)

<hr class="subsection-divider" />

<h3 id="demo">Demo</h3>

We will likely demonstrate that it will squish a bug-shaped object that is on the plate while it rotates. We will place a small, approximately lanternfly-shaped object with flexible properties on the top table of the trap, then rotate it to show how the fly will be squished if it doesn’t move to the center of the trap.

</div>