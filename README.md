# Power-Outage-Priority
A web app that helps households prioritize which appliances to power during an outage based on available backup power and appliance needs .

Power Priority

Power-Outage-Priority Calculator

The Inspiration — 

Power outages can leave households with limited backup electricity while multiple appliances are running at the same time. In that situation, people may know their battery or UPS capacity, but not how long it will actually last or which appliances are consuming the most power.

We wanted to turn this everyday problem into a simple, practical tool. During the hackathon, we built Power Priority to help people quickly understand their available backup power and make more informed decisions about appliance usage during an outage.

What It Does — 

-  Backup Runtime Calculation — Estimates how long available battery/UPS energy can power the selected appliances.
- Power Load Analysis — Calculates the combined wattage of household appliances and identifies the highest-consuming devices.
-  Priority Planning — Lets users classify appliances as Essential, Important, or Optional to support outage decision-making.
-  Built-in Guide — A simple help button explains how to use the calculator for first-time users.

How We Built It — The Tech Stack

Frontend

- HTML5
- CSS3
- Vanilla JavaScript

Backend

- None — fully client-side

Database & Cloud

- None required

APIs / AI / Web3

- None

The entire application runs directly in the browser, making it lightweight and easy to deploy with GitHub Pages.

Challenges We Ran Into

One challenge was making the calculator useful without overwhelming users with electrical calculations. We solved this by reducing the inputs to the most important values—battery capacity, usable battery percentage, inverter efficiency, outage duration, and appliance wattage.

Another challenge was creating a responsive interface that feels natural on both mobile and desktop screens. We used a responsive CSS layout and simplified the interface into clear cards, inputs, results, and a built-in help guide.

Accomplishments We're Proud Of

- Built a complete working calculator using only HTML, CSS, and JavaScript.
- Created a responsive interface for both mobile and desktop.
- Turned electrical calculations into an easy-to-understand household decision tool.
- Added appliance priority classification to make the results more practical.
- Kept the application lightweight with no backend or installation requirements.

What We Learned

We learned that solving a real-world problem isn't only about making complicated technology. A simple calculation can become much more useful when it is presented in a way that helps people make an actual decision.

We also learned the importance of balancing accuracy, simplicity, and user experience when designing a calculator for everyday users.

What's Next for Power Priority?

Short-Term

- Automatic recommendations for which appliances to switch off.
- Appliance startup/surge power support.
- Solar panel and generator support.
- Battery voltage and Ah-based calculations.
- Visual energy-use charts.

Long-Term

Power Priority could evolve into a broader household energy-management platform that helps users prepare for outages, optimize backup resources, and understand their household energy resilience.

