Reasonable Care Front End and UX Repository

This Repository holds all of the frontend code for the reasonable care rpoject.

All code in this repository was written by Nick Usoff with the help of the
bootstrap documentation

-------------------------------------------------------------------------------

I. What is Reasonable Care?

Reasonable Care is a web application which allows users to browse health care
plans and come to a conlusion about which plans they would like to look into
further. Users are allowed to select which of four metrics they would like to
factor in to their search (they are all on upon page load). These metrics are:
deductible vs. Premium, co-pays for primary care, co-pays for a specialist, and
co-pays for a specialist. Resulting plans are then assigned a 0-4 star score in
each of those metrics which the user has turned (or left) on.


II. Why did we build it?

This project is intended to show that good UX and better use of data can create
a better experience for peoplw searching for health insurance on an exchange.
We hope that our implementation will be seen as a better version of the current
MA Health Connector, and that this shows that the experience doesn't need to be
as bad as it is now. In addition to the UX, we have also created a public API,
which we believe will help others who want to go down the same path we did to
create a better implementation of the exhange. We made our API public to ensure
that anyone can access the data set we put together.


III What hasn't been completed yet?

At this point, Reasonable Care is a proof of concept. There are a limited
number of ways to filter results, and many of those even are simplified to,
say, only apply to healthy 27 year olds who don't smoke. But the general ideas
are all there, and I hope we've proven in creating this that it is possible to
make something that functions to help MA residents choose health insurance that has a better user interface than the MA Health Connector.