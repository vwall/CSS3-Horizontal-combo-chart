A simple horizontal combo chart, serving the same purpose as a pie chart, except it's fluid, rectangular, and isn't as gimmicky as a pie chart. To use, paste this into your html:

	<div class="horizontal-combo-container">
		<div class="horizontal-combo-mortice">
			<div class="combo-fill" style="width: 35%">
				<span class="combo-label">Campaigns</span>
				<span class="fill-amount">35%</span>
			</div>
		</div>
	</div>

Then, link to the included stylesheet in the head of your html. For each new summary of data, create a new combo-fill element containing its own combo-label and fill-amount.

See the example.html for colors and styles.

