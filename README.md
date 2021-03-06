# Transshipment-and-Risk-Minimizing-Problem

Part 1: Rockhill Shipping & Transport Company 
 
Allen, a manager of the South-Atlantic office of the Rockhill Shipping & Transport Company is 
negotiating a new shipping contract with Chimotoxic, a company that manufactures chemicals for 
industrial use. Chimotoxic wants Rockhill to pick up and transport waste products from its six plants to 
three waste disposal sites. Allen is very concerned about this proposal arrangement. The chemical 
wastes that will be hauled can be hazardous to humans or the environment if they leak. In addition, 
some of the communities in the regions where the plants are located may prohibit hazardous materials 
from being shipped through their municipal limits. Thus, not only the shipments have to be handled 
carefully and transported at reduced speeds, but they may also have to traverse in circuitous routes in 
some cases.  
Allen has estimated the cost of shipping a barrel of waste from each of the six plants to each of the 
three waste disposal sites as shown in the following table.  
 
 Waste Proposal Site 
Plant: Orangeburg Florence Macon 
Denver $12 $15 $17 
Morganton 14 9 10 
Morrisville 13 20 11 
Pineville 17 16 19 
Rockhill 7 14 12 
Statesville 22 16 18 
Table 1: Shipping costs, per barrel of waste from six plants to three waste disposal sites  
 
 
 
The plants generate the following amounts of waste products each week: 
 
            
 
 
2 
 
 
Plant: Waste per Week (bbl) 
Denver 45 
Morganton 26 
Morrisville 42 
Pineville 53 
Rockhill 29 
Statesville 38 
Table 2: Total Waste generated by each plant  
 
The three waste disposal sites at Orangeburg, Florence, and Macon can respectively accommodate a 
maximum of 65, 80, and 105 barrels per week.  
 
In addition to shipping directly from each of the six plants to one of the three waste disposal sites, Allen 
is also considering using each of the plants and the waste disposal sites as intermediate shipping points. 
In this case, trucks would be able to drop a load at a plant or a disposal site to be picked up and carried 
on to the final destination by another truck. Furthermore, Rockhill would not incur any handling costs 
because Chimitoxic has agreed to take care of all the handling costs at the plants and at the disposal 
sites. In other words, Rockhill???s only cost will be the transportation cost. Therefore, Allen wants to be 
able to consider the possibility that it may be cheaper to drop and pick up loads at intermediate points 
rather than ship them directly.  
Allen has estimated the shipping costs per barrel between each of the six plants to be as follows:  
 
 Plant 
Plant: Denver Morganton Morrisville Pineville Rockhill Statesville 
Denver $--- $3 $4 $9 $5 $4 
Morganton 6 --- 7 6 9 4 
Morrisville 5 7 --- 3 4 9 
Pineville 5 4 3 --- 3 11 
Rockhill 5 9 5 3 --- 14 
Statesville 4 7 11 12 8 --- 
Table 3: Shipping costs, per barrel of waste from each plant to another plant  
 
 
 
The estimated shipping cost per barrel between each of the waste disposal sites is as follows:  
 
 Waste Proposal Site 
Waste Disposal Site: Orangeburg Florence Macon 
Orangeburg $--- $12 $10 
Florence 12 --- 15 
Macon 10 15 --- 
Table 4: Shipping costs, per barrel of waste between the three waste disposal sites  
 
 
Allen wants to determine the shipping routes that will minimize Rockhill???s total cost in order to develop 
a contract proposal to submit to Chimotoxic for waste proposal. He particularly wants to know if it 
would be cheaper to ship directly prom the plants to the waste sites or if he should drop and pick up 
some loads at the various plants and waste sites.  
            
 
 
3 
In the word document, explain the details of the solutions obtained for the optimal routes and their 
respective optimal costs for both cases. In particular for the case when loads are dropped and picked up 
at various plants and waste sites, explain how many barrels, in total, will be transported each week from 
a source to a destination.  
 
 
Part 2: Investment Allocations 
 
An investor has selected the following asset types in his portfolio. The expected return for each asset 
type has been estimated by using the historical data: 
  Expected Returns 
Bonds 7% 
High tech stocks 12% 
Foreign stocks 11% 
Call options 14% 
Put options 14% 
Gold 9% 
Table 5: Expected returns of Investments 
 
The following table indicates the covariance matrix of the assets??? returns. Each diagonal entry is the 
variance of an asset and non-diagonal entries are the covariances between any pairs of assets.  
 Bonds High tech 
stocks 
Foreign 
stocks Call options Put options Gold  
Bonds 0.001 0.0003 -0.0003 0.00035 -0.00035 0.0004 
High tech stocks   0.009 0.0004 0.0016 -0.0016 0.0006 
Foreign stocks     0.008 0.0015 -0.0055 -0.0007 
Call options       0.012 -0.0005 0.0008 
Put options         0.012 -0.0008 
Gold           0.005 
 
Table 6: The Covariance matrix of assets??? returns 
 
(i) Suppose that our investor wishes to invest $10,000 in this portfolio. Determine how he 
should allocate this investment to the individual assets in his portfolio in order to have a 
minimum baseline expected return of 11%, and at the same time, at a minimum risk.  
(ii) Let the solution pair be denoted by (r, e), where ???r??? denotes the minimized risk and ???e??? 
denotes the expected portfolio return after the problem is solved. Use successive values of 
10%, 10.5%, 11%, 11.5%, 12%, 12.5%, 13% and 13.5% as the baseline return values to obtain 
eight pairs of solutions (r, e).  Plot ???e??? versus ???r???. Explain whether there exists a pattern in 
this plot. In other words, explain, in your opinion, the type of mathematical relationship that 
???r??? and ???e??? may have. 
