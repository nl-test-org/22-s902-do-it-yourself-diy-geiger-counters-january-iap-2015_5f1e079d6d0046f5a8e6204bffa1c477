---
course_id: 22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015
layout: course_section
menu:
  leftnav:
    identifier: 0b9a6b9b5bf6bb2b733c8567fa220058
    name: Labs
    weight: 110
title: Labs
type: course
uid: 0b9a6b9b5bf6bb2b733c8567fa220058

---

WARNING NOTICE:

An activity described in this course is potentially hazardous and requires a high level of safety training, special facilities and equipment, and supervision by appropriate individuals. You bear the sole responsibility, liability, and risk for the implementation of such safety procedures and measures. MIT shall have no responsibility, liability, or risk for the content or implementation of any of the material presented. [Legal Notice](/terms/)

During lab periods, students build their own Geiger counter, and then characterize their counter, the background radiation in the room, and its shielding properties, using the tools and software described below.

Building the Geiger Counter
---------------------------

The MIT students enrolled in this class were given a kit containing all the parts required to build their Geiger counter, and a set of detailed instructions. 

*   Parts list (choice of two file formats): [Bill of Materials (XLS)](/coursemedia/22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015/56f6632820791cdbee270133f311a740_MIT22_S902IAP15_Rev6BOM.xlsx), [Bill of Materials (PDF)]({{< baseurl >}}/sections/labs/mit22_s902iap15_rev6bom) (Courtesy of Mark Chilenski. Used with permission.)
*   [Instructions to build your Geiger-Müller Counter (PDF - 5.2MB)]({{< baseurl >}}/sections/labs/mit22_s902iap15_gc_instruct) (Courtesy of Mark Chilenski. Used with permission.)
*   ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[Geiger Counter schematic diagram (PDF - 1.1MB)]({{< baseurl >}}/sections/labs/mit22_s902iap15_lab_shmatc) (Courtesy of Mark Chilenski. Used with permission.)

A soldering iron is also required.

### How Can I Obtain the Parts?

OCW cannot provide this parts kit to you directly, but we can offer tips on how to obtain the parts yourself. The Bill of Materials file above lists all of the parts, and the Instructions gives more details about how the parts are used for each step.

*   In 2015, the parts would cost $60-$100 US (depending on your source).
*   Most parts should be readily available from any electronics retailer.
*   The SBM20 Geiger-Müller tube can be purchased on [eBay](http://www.ebay.com).
*   Circuit board fabrication companies can make the board for you, using the specification in these [Gerber files (ZIP)](/coursemedia/22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015/0dd01977ae3f5be78d628cae74d4e615_lab_gerber.zip) (This ZIP file contains: 1 .gbl file, 1 .txt file, 1 .gbo file, 1 .gtl file, 1 .gts file, and 1 .gto file). One such company is [Advanced Circuits](http://www.4pcb.com/). Shop for student specials on a single or small number of boards. 
*   The plastic case is a [Serpac 052C](http://www.serpac.com/052c.aspx), which can be ordered from electronics retailers like [DigiKey](http://www.digikey.com/product-detail/en/052C,BK/SR052-CB-ND/2206037).
*   The case must have holes drilled in its sides, in order to let the beta particles through. While the MIT kit's case was custom machined on a CNC to produce letter-shaped holes, any shape holes in the middle of the sides will do. Refer to these mechanical drawings for guidance on the proper location of the holes: ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[top-view drawing (PDF)]({{< baseurl >}}/sections/labs/mit22_s902iap15_casetop) and ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[bottom-view drawing (PDF)]({{< baseurl >}}/sections/labs/mit22_s902iap15_casebtm).

**NOTE** (July 2015): If OCW users express sufficient interest, the MIT Department of Nuclear Science and Engineering might offer this kit for sale to the public. If you are interested, please let them know by completing this brief [web survey](https://survey.zohopublic.com/zs/JIiBBQ).

Tools and Software
------------------

Labs use the [National Instruments ELVIS II](http://sine.ni.com/nips/cds/view/p/lang/en/nid/205425) system and MIT-provided software running on a Windows personal computer to collect data about the Geiger counter.

Begin by installing the National Instruments LabVIEW Run-Time engine and NI-DAQmx Run-Time engine. The versions of these programs used during the January 2015 MIT class are linked below.

*   [LabVIEW Runtime Engine 2014](http://www.ni.com/download/labview-run-time-engine-2014/4887/en/)
*   [NI-DAQmx 14.1 Runtime Engine](http://www.ni.com/download/ni-daqmx-run-time-engine-14.1/4954/en/)

Note that these programs are updated frequently; consult the [NI Hardware Drivers page](http://www.ni.com/downloads/ni-drivers/) for the latest versions.

### MIT NSE Geiger Data Collection Program

After installing the above National Instruments programs, next install the [MIT NSE Geiger Data Collection Program (EXE - 1.8MB)](/coursemedia/22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015/0772d8c74905d75b9b6c9e6e1ee762d4_MITNSECounter.exe) (Courtesy of Matthew D'Asaro. Used with permission.) Detailed instructions for its use are displayed when you run the program.

_Please note_: This software is provided "as-is," and OCW cannot offer any further technical support.

Technical requirements:

*   The software is designed to work with the NI-ELVIS II system. Most likely, it should also work with a wide variety of other NI data acquisition hardware (i.e. the NI-USB-xxxx series), but this functionality is untested.
*   The following software environment is required:
    *   Windows XP or newer
    *   NI LabVIEW runtime engine 2014 or newer
    *   NI NI-DAQmx runtime 14.1 or newer

Lab Report
----------

Having built their Geiger counter, each student performed a series of lab tests and activities with it, and wrote up a lab report.

[Lab Description and Report (PDF)]({{< baseurl >}}/sections/labs/mit22_s902iap15_lab01)

{{< anchor "images" >}}{{< /anchor >}}Image Gallery
---------------------------------------------------

Here are some photos of the Geiger counter kit and students working in the lab.
{{< image-gallery id="0b9a6b9b5bf6bb2b733c8567fa220058_nanogallery2" baseUrl="/coursemedia/22-s902-do-it-yourself-diy-geiger-counters-january-iap-2015/" >}}
{{< image-gallery-item href="8806deeb408cb649ce8cf1b0f39a5beb_01_built.jpg" data-ngdesc="The assembled Geiger counter. Photo by Mark Chilenski." text="The assembled Geiger counter." >}}
{{< image-gallery-item href="08fb374241c1acec9d4bd6e549b54f5d_02_kit.jpg" data-ngdesc="The parts that comprise the Geiger counter kit. Photo by Mark Chilenski." text="The parts that comprise the Geiger counter kit." >}}
{{< image-gallery-item href="2722c55e6634a9cc994d1b5be187ebb9_03_lab.jpg" data-ngdesc="Students assembling their Geiger counters in the lab. Photo by Mike Short." text="Students assembling their Geiger counters in the lab." >}}
{{< image-gallery-item href="6b0abc6e95bebf78f24059838f49d34e_05_solder.jpg" data-ngdesc="Soldering is one of the skills developed in this course. Photo by Mike Short." text="Soldering is one of the skills developed in this course." >}}
{{</ image-gallery >}}