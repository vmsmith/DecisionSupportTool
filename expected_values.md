[README](https://github.com/vmsmith/DecisionSupportTool/blob/master/README.md)

### Expected Values (EV)  

#### Introduction  

Expected values (EV) are

Michael Maubboussin  

>“Expected value...is the weighted-average value for a distribution of possible outcomes. You calculate it by multiplying the payoff (i.e., stock price ) for a given outcome by the probability that the outcome materializes.”

The easiest way to...

#### Scenario #1  

Imagine a farmer in Kansas trying to decide whether to plant soybeans or wheat. In previous years he planted soybeans and did quite well selling them to China. This year, however, the is sabre rattling between the U.S. and China, and the threat of a trade war looms. In the case of a trade war, he would probably not do well planting soybeans.

There are several elements to consider.

First, the farmer has two *courses of action*. These are thing the farmer can control: plant soybeans, or plant wheat.

Second, there are two possible *states of nature*. These are things the farmer cannot control: there is a trade war, or there is not a trade war.

The farmer begins by organizing the courses of action and the states of nature in a 2 x 2 matrix:

<table>
  <tr><td></td><td>No Trade War</td><td>Trade War</td></tr>
  <tr><td>Plant Soybeans</td><td></td><td></td></tr>
  <tr><td>Plant Wheat</td><td></td><td></td></tr>
</table>  

There are four possible outcomes, or payoffs, and the farmer's next task is to identify -- to the best of his ability -- what those payoffs might be.

**Payoff 1:** Farmer plants soybeans and there is no trade war. The farmer knows this sceario pretty well as it has been the status quo for some time. If he plants soybeans and there is no trade war, he can expect to make roughly $1,500 per acre.

**Payoff 2:** Farmer plants soybeans and there is a trade war. The farmer believes that he would actually lose money in this scenario since he and hundreds of other farmers would be flooding the market with soybeans, and without China as a buyer, the market would be over-saturated. In this scenario he thinks he's lose $750 an acre.

**Payoff 3:** Farmer plants wheat and there is no trade war. Although wheat is not as profitable as soybeans, there is a decent steady demand globally. If the farmer planted wheat under this scenario, he think he would make $1,000 an acre.

**Payoff 4:** Farmer plants wheat and there is a trade war. The farmer thinks he would make money in this scenario, only not as much since many other former soybean farmers would probably also be planting wheat. In this scenario the farmer thinks he would make $500 an acre.

Now the farmer can fill in his matrix:

<table>
  <tr><td></td><td>No Trade War</td><td>Trade War</td></tr>
  <tr><td>Plant Soybeans</td><td>+$1,500</td><td>-$750</td></tr>
  <tr><td>Plant Wheat</td><td>+$1,000</td><td>+$500</td></tr>
</table> 

The next step in the process is to determine the probabilities of the two states of nature.

The farmer reads all he can on the topic, he writes to his two Senators requesting their views, he attends a town hall meeting with his Congressional representative to discuss it, he meets with the local Department of Agriculture people, and he discusses it vigorously with his fellow farmers.

The farmer eventually decides that the probability, &alpha;, of no trade war is 0.60. Therefore, the probability that there *is* a trade war is 1 - &alpha;, or 0.4. The decision matrix now looks like this:

<table>
  <tr><td></td><td>No Trade War<p>&alpha; = 0.6</td><td>Trade War<p>1 - &alpha; = 0.4</td></tr>
  <tr><td>Plant Soybeans</td><td>+$1,500</td><td>-$750</td></tr>
  <tr><td>Plant Wheat</td><td>+$1,000</td><td>+$500</td></tr>
</table> 

Next, the farmer multiplies the probabilities associated with each state of nature times the payoffs in that column:

<table>
  <tr><td></td><td>No Trade War<p>&alpha; = 0.6</td><td>Trade War<p>1 - &alpha; = 0.4</td></tr>
  <tr><td>Plant Soybeans</td><td>+$1,500 * 0.6 =<p>+$900</td><td>-$750 * 0.4 = <p>-$300</td></tr>
  <tr><td>Plant Wheat</td><td>+$1,000 * 0.6 = <p>+$600</td><td>+$500 * 0.4 = <p>$200</td></tr>
</table> 
