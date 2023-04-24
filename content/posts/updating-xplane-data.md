---
title: "Updating Navigation Data in X-Plane"
description: "Successfully eliminating the Nav Data Out of Date warning."
tags: ['training', 'simulation', 'xplane']
lastmod: 2023-04-24
draft: false
---
I use [X-Plane 12](https://www.x-plane.com) for procedure proficiency in instrument training.  It's much easier to set up scenarios and quickly modify the environment to increase proficiency.  I've always been bothered, though, by the warning in the GNS430 and G1000 that the navigation data was out of date.  This is the real warning that we get in the airplane when the nav data is out of date, but there's not a database subscription service that I can order through Garmin to keep the virtual avionics current.

I spent some time digging through a variety of online discussions, and while there are paid services that can keep you updated, the FAA also freely publishes the data that I need to update the nav data in X-Plane so that the instrument procedures on my EFB match the flight data in the nav database of the simulator.

The FAA's [Coded Instrument Flight Procedures (CIFP)](https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/cifp/download/) data can be directly loaded into X-Plane, with some small modifications.  This is the ARINC 424-formatted data, which X-Plane 12 natively supports as a data format.  This is incredibly handy, and I don't know why it's not more often publicised.  This is a huge benefit for instrument training and proficiency.

### Data Loading Procedure
1. Download the current CIFP data from the [FAA website](https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/cifp/download/) and unzip/extract the downloaded data.
2. Rename the `FAACIFP18` file to `earth_424.dat`.
3. Move the `earth_424.dat` file to the X-Plane `Custom Data` folder.
4. Launch X-Plane, and it will automatically load the custom data.

One warning about this, which isn't a deal breaker for me, but might be for you.  In the file that you downloaded from the FAA is a helpful spreadsheet called "Not In CIFP."  These are procedures that will be missing from your nav database in the simulator's avionics when the update is performed.

These excluded procedures eliminate an ILS and LOC approach to one of my home airports, but I can manually tune in the localizer and fly the approach with "raw data."  I suspect this approach isn't included because it isn't "GPS Required" for the approach or missed procedures, instead requiring radar to identify the Initial Approach Fix.  The missed approach procedure requires intercepting and tracking a VOR radial to reach the Missed Approach Fix.  Honestly, I can't think of a better scenario for an approach when I want to answer the question, "what happens when GPS stops working?"