OpenRTB - time, confidence, energy
==================================

  -------------- ---------------------
  **Created:**   *8/18/2019 4:57 PM*
  **Updated:**   *8/18/2019 5:04 PM*
  -------------- ---------------------

\

{ 1/probability ; 1/std dev ; } = rata pariu

{ - dt } = scaderea rezervei de timp (proces de timp finit; rezerva
pozitiva sau negativa)

{ - dE } = scaderea rezervei de energie (creste supraliniar cu
acuratetea; 1/p(err); 1/erfi(p) ; 

\

Time token - finite amount

Accuracy token - theoretically infinite amount; (lg2 (1-p) ) \^2 ;
bounded at lg2(1-epsilonMachine)); represents number of binary choices
needed to make a determinination; scanBit type of accuracy -\> overall
accuracy is given by erf(p)\*sigma, guaranteed accuracy stops at first
dissimilar bit;

 
