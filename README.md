# atd-data-analysis
This data analysis is part of my project looking into U.S. Immigration and Customs Enforcement (ICE)'s [ISAP](https://www.dhs.gov/sites/default/files/2022-06/ICE%20-%20Intensive%20Supervision%20Appearance%20Program%2C%20FYs%202017%20-%202020.pdf) program under [Alternatives to Detention (ATD)](https://www.ice.gov/features/atd). 

In the ISAP (Intensive Supervision Appearance Program), immigrants awaiting their immigration hearings and those generally in removal proceedings are enrolled into different types of monitoring technologies. This is for ICE to keep track that enrollees are following the requirements and procedures posed by ICE.

ICE does this through a variety of technologies. As of Aug. 2023, the technologies used include GPS ankle monitors, a phone app called BI SmartLINK, and VoiceID through phone calls. Most recently, VeriWatch, a wristband version of the GPS ankle monitor, is put into a pilot program in Colorado.

The catch is, all of this is not done by ICE directly. Instead, ICE contracts a for-profit  company called [BI Incorporated](https://bi.com/) for:

- The production of all of these technologies;
- The direct monitoring and communication of all migrants enrolled in the program and using these technologies;
- The maintenance of a database which stores all of the enrollees' information.

The ATD program started in 2004, but grew significantly in recent years, especially with the phone app SmartLINK under the Biden administration. As a result, BI has become a big beneficiary of ICE's ATD program. 

In the folder [atd-finances], I analyze the amount ICE pays BI each fiscal year after downloading the contract spending data from [usaspending.gov](usaspending.gov). I use the higher-level summary data instead of transaction data because the summary data shows which specific contract each row is for. 

To put contract spending to BI in correlation with tasks ICE required of BI, I made the methodological choice of dividing the contract amount by the number of fiscal years it spans. For example, if ICE contracted BI for the deployment of program A for x million dollars, to pay for BI's service from FY 2011-2015, then I would divide x by 5 years, even if the entire payment was made in 2011. 


