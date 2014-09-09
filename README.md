Qlik Sense Extension - Grid Chart
================================================================================
This extension creates a grid chart similar to the one found in QlikView 11.

**Implementation**
The grid chart takes 2 dimensions and 1 to 2 measures:

Dimension 1: This dimension is for the x-axis.

Dimension 2: This dimension is for the y-axis.

Measure 1: This measure controls the bubble size.

Measure 2 (optional): This measure allows you to define a custom color based on the dimension and measure data. For example, you could create a measure that colors the bubbles red when they pass a certain threshold, but blue otherwise.


If you do not choose to use Measure 2 to control the color based on the data, you can define a global color for all bubbles in the Properties panel, under "Appearance>Color". You can also set auto-transparency on or off in this menu. The transparency setting will apply transparency to the bubbles based on their size.