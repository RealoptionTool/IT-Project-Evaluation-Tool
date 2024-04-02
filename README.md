# ITprojectevaluationtool
The [IT project evaluation tool](https://personal-2u8rb8tg.outsystemscloud.com/ITInvestmentprojectEvaluation/Login) estimates the value of strategic growth options for IT projects. After providing the system with some characteristics (e.g., interest rate used for calculation, project runtime, cash flows), it simulates the expected option value based on 100,000 iterations. It returns the expected option value, the return on investment as well as the 95% confidence interval for the estimation. You can use the public account "Andrea McKenzie" or register and use your own account, so only you can see your projects.

The tool is based on the modified assumptions (A1', A3' and A4') from [Müller et al. (2016): Decision Support for IT Investment Projects](https://link.springer.com/article/10.1007/s12599-016-0423-7). It allows all inflows and outflows to follow GBM or GMR, and it can also account for unforeseeable events that may affect the value of the IT investment project (referred to as jumps in the paper). If cash flows are uncertain, they can either be unbounded and follow GBM or they convert to their long-term value and follow GMR. Shocks are modelled using a lognormally distributed random variable.
