<H1> FinTech_Casestudy</H1>


<H2> Case Study of FinTech company </H2>

<H3> Case Study Proposal </H3>



##  The Bank of America Quartz Platform 
![Image](https://github.com/pdevalaraju/FinTech_Casestudy/blob/master/download.png)


## What Is It

### Quartz is Bank of America Merrill Lynch's integrated trading, position management, pricing and risk management platform. And the key word is “integrated”: developers can share the same data via Sandra, a proprietary object-oriented database, the same Python codebase, and the same proprietary integrated development environment.


## Why This Matters
### It’s hard to imagine a data processing issue within Bank of America for which this doesn’t matter. Historically, different businesses within financial institutions, such as foreign exchange trading, bond trading, etc., each had their own “silo-ed” (i.e. stand-alone), and often incompatible computer systems. This meant that any kind of aggregation over all such systems, required to determine the total amount one financial institution owed another, netted over all of its different business lines, was a computational nightmare. Goldman Sachs’ version of Quartz, known as SecDB, was the first of the integrated systems that avoided the silos. SecDb was widely credited with helping Goldman avoid the worst of the 2008 banking crisis (What few people know is that the difficulty that banks had in figuring out what they were owed by other banks was a major issue in the banking crisis
<ol>
<Li> If Bank X didn’t know how much they could expect to receive, in total, from Bank Y, then they wouldn’t know how much had to be raised from other sources if Bank Y couldn’t pay. Bank X therefore had to assume the worst and not make any more loans to its own customers.). So, in the wake of the crisis, a number of banks scrambled to copy SecDB, including Bank of America. Meanwhile, Python was invented, so the SecDB look-alikes used Python instead of Goldman’s home-grown language, Slang. </Li>

<Li>
Banks wanted such systems for less dramatic reasons, as well. With Quartz, when something new needs to be done, such as the rolling out of a new financial product, or responding to a new regulatory request, relevant code and data from previous work can be retrieved and used “right out of the box”. Also, the kind of firm-wide risk management calculations required by regulators are extremely painful to do without something like Quartz. For example, regulators require quarterly backtests involving the entire Bank-wide portfolio of financial derivatives (options, etc.). </Li>

<Li>Before Quartz, the backtesting team was hard pressed to complete the tests in the three months between reporting periods. With Quartz, the tests took only a few days, and most of that time was waiting for the calculations to finish. </Li>
</ol>

## Why This May Be Interesting ##

### A case study on this topic could

<Ul>
<LI>Illustrate a technology’s transition from a back office utility to a core aspect of business strategy for the largest financial institutions (It is all too easy for a fintech student to forget that financial technology is always used in a larger business context;</li>
<LI>Introduce students to a technology ecosystem that is popular with a number of major investment banks (In addition to Goldman’s SecDB and Bank of America’s Quartz, JP Morgan Chase has a similar system called Athena, and Deutsche Bank and Credit Suisse are reportedly also in the game. Furthermore, some of the architects of Quartz have started their own company to reproduce Quartz-like functionality in the cloud.); </li>

<LI>Present an important banking use case for object oriented Python (Many financial products and many kinds of financial market data map nicely into Python objects, a fact that certainly has not been lost on the designers of Quartz!);</li>

<LI>Raise design issues involved in building both the Quartz infrastructure and applications built on top of Quartz.</li>

<LI>There are a wealth of Quartz related openings at Bank of America in both New York and Charlotte, North Carolina. In principle, it is possible to join Bank of America through campus recruitment or through their careers website. There are also opportunities to work in New York on Python based, Quartz-like systems at other investment banks, most notably JP Morgan’s Athena project (I’m told that JP Morgan actually does invite people for interviews if they register with the JP Morgan career website.).</li>

<LI> Beacon Platform, the stand-alone company that is developing a Python based, Quartz-like system in the cloud, is also hiring (Beacon is small enough that an email to one of the principals will be sufficient to start a conversation.). Pythonistas might even have a hope of working with Goldman’s venerable SecDB, as the core Slang functionality is being given a Python wrapper.</li>

<LI>The stated requirements for many of these roles often include a certain number of years of paid experience because the work requires the comprehension of thousands, if not tens of thousands of lines of complex object-oriented Python code. It helps to understand the business purpose of the code.</li>

<LI>Demand for people to work on the above systems is likely to increase because many current staff are immigrants here on those ever-scarcer H1-B visas.</li>
</ul>

**Things to Keep in Mind for a Case Study**
<ul>
<Li>A general discussion of the data processing required to support a large scale capital markets (i.e. whole sale banking) business, including the calculations required to value and measure the risks associated with a portfolio of deals. A sample calculation in which the value and the appropriate hedges for an interest rate swap in Euro could be used to illustrate 
<ul>
<li> How market data enters into such a calculation </li>
<li>The importance of a reference “yield curve” for time value of money calculations </li>
<li>The multiple financial instruments that become relevant and must therefore be tracked
when the deal is hedged
</li>
</Ul>
<LI>The implications of the historical, “silo’ed” approach, as reflected in Mark Higgins’ piece, below.
<LI>Updates about how the ecosystem is growing </LI>
</ul>

A use case of Quartz: either the regulatory reporting exercise described above or a daily estimate of market risk, which is easier to explain Resources:


 [One of many, many web ages explaining swap prpicing](https://www.fincad.com/resources/resource-library/wiki/swap-pricing) 

 [The saga of SecDB, Athena, and Quartz, as told on a financial recruiting web site.](https://news.efinancialcareers.com/uk-en/276170/secdb-quartz-athena-analytics)

<Li> [more about SecDB](https://news.efinancialcareers.com/uk-en/147434/inside-goldman-sachs-secret-sauce/) </li>
<Li> [the skinny on Quartz – and Quartz internal politics - from a variety of people in the trenches](https://www.quora.com/when-why-and-to-what-extent-did-Bank-of-America-rebuild-its-entire-tech-stack-with-Pytho)  </li>
<Li> [One of the architects of SecDB, Athena, and Quartz, now at Beacon Platform, explains the
rationale behind such systems.](https://www.linkedin.com/pulse/getting-most-out-your-quant-team-building-iqp-mark-higgins/)
</li>
<Li>[Website for Beacon Platform] (https://www.beacon.io/)
</OL>