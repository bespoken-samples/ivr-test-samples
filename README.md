# IVR Test Sample
This project contains a simple Bespoken end to end test for IVR systems. In it, we call American Airlines and ask for a new flight reservation, simulating a real call.

<p style="text-align:center">
<img src="https://bespoken-samples.s3.amazonaws.com/images/ivr-excerpt.gif" style="max-width: 60%;">
</p>

The test is able to identify when to move to the next interaction via the `finishOnPhrase` property, when to repeat an interaction via the `repeatOnPhrase` property and is able to simulate key pad inputs as well. For more information on our IVR tests visit: [https://read.bespoken.io/end-to-end/ivr/](https://read.bespoken.io/end-to-end/ivr/)

## How to run this?
1. Apply for a free Bespoken trial at: https://apps.bespoken.io
2. Create your own Virtual Device: https://read.bespoken.io/end-to-end/setup/
3. Replace your Virtual Device Token here: 
4. Install the Bespoken CLI: `npm install -g bespoken-tools`
5. Clone this project and run: `bst test` in your command line