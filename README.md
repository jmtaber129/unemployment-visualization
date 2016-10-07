# US Unemployment Visualization
An interactive time series visualization of US unemployment data using D3.  Created for Project 1 of CS 4331/5331 - Visualization and Visual Analytics at Texas Tech University.

#### Click the image below to watch a short video demo.
[![ScreenShot](http://myweb.ttu.edu/jataber/unemployment/p1.taber.james.png)](https://youtu.be/Eg6DPIKl2Ks)

The web application can be viewed at www.myweb.ttu.edu/jataber/unemployment.

The application, which presents unemployment time series through small multiples, provides several different features for analyzing unemployment trends in the US.  The application provides an intuitive user interface, including a state selection list, time interval options, and series comparison options.  Users can also select states from an interactive map of the US.  To compare states or years, users select the corresponding option, and click the "Update Chart Options" button.  The application then displays a difference chart for each series, in which the positive and negative differences between the compared features are emphasized by colored areas above and below the original series' line.

The data used by this application was obtained from the Bureau of Labor Statistics (bls.gov). Raw state unemployment rate data was processed into CSV format with date, state, and rate by CS 5331 student Vibhuti Gupta using an R script.

### The Effects of Hurricane Katrina on US Gulf State Unemployment
From the visualization, it is obvious that Hurricane Katrina (Aug. 2005) had a substantial impact on the unemployment rates of Louisiana and Mississippi, but had almost no impact on the rates of the other gulf states.  Interestingly, the unemployment rate of Louisiana is consistently lower than the national average starting just 6 months after Katrina.

![Alt text](/screenshots/hurricane-katrina-unemployment.PNG?raw=true "Hurricane Katrina")

### The Effects of the 2008-09 Financial Crisis on different states
Another interesting finding from the visualization is the variety of effects the '08-09 financial crisis had on different state's unemployment.  For some states, the viewer can see that unemployment rose gradually over several years before peaking.  In Nevada, for example, the rate rose from 5.6% in Jan 2008 before peaking at around 13.5% throughout 2010.  In other states, unemployment rose sharply over the course of a few months before peaking.  In Oregon, the rate rose from 6.4% in Sept 2008 before peaking 5 months later in March 2009.  For a few states, like Alaska, the crisis had little to no effect on local unemployment.

![Alt text](/screenshots/financial-crisis-09.PNG?raw=true "08-09 Financial Crisis")

TODO(jmtaber129): Add more findings here.
