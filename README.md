# server_monkey

a company can have multiple credits and on those credits there are contacts that work at the company


API CONNECTIONS
hubsot
google analytics
salesforce
netsuite

fraud system (idk the name)

Taxes change from various locations, it's not set in stone thoroughout a large area.
Api to Connect to Tax system to populate our db in the morning.

30 in a full day - May 28
6 orders in a hour is a lot

280k - bank transfer (2022)
416k - bank transfer

just shy of 65,000 for credit or debit
paypal wont accept orders over 65k 


BRAIN TREE paypal system - just not payflow
better fraud rules ??

PAYMENT RULES?
$payment->checkRules();//configurable via admin portal
if(!$payment->valid && $payment->hasErrors())
{
  log($payment->errors());
  return $payment->errors();
}

have a log json file indicator for showing status logs in browser and being able to view them properly



mandrill for email system
use backup system??





