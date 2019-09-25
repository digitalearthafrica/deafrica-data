DEA S3 Direct Access Disclaimer:
~~~~~~~~~~~~~~~~~~~~~~~~~
While Digital Earth Africa is committed to releasing its data to the public
for free, the unfortunate reality is that data leaving (data egress) the AWS
Oregon region incurs a non-trivial cost to DEA. In the future, to avoid out of
control costs for hosting our data, we may need to enable "Requester Pays" on
the data provided here.
 
This will mean:
 * Data that is transferred from this bucket to AWS compute resources and 
   services within the AWS Oregon (us-west-2) will remain free of cost;
 * All other downloads will require a user have an AWS account, this AWS 
   account will incur the charges for data egress.
The data itself will still provided free under a "CC BY Attribution 4.0 
International License" (https://creativecommons.org/licenses/by/4.0/legalcode)
 
If you would like to avoid disruption if and when and if this change is 
applied, you will need to configure your S3 download client to use an AWS 
account/identity and send the accept requester pays header 
'x-amz-request-charged:requester' most clients offer a simple checkbox or 
configuration flag to accept requester pays. 

For all enquiries, please contact Earth.Observation@ga.gov.au.

