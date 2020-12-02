# kb_sdk_test_harness

to run, create the file "config/test.cfg" with the following content:


---------------------------------------------------------------------
# PLEASE DO NOT COMMIT THIS FILE INTO GIT REPO !!!
#
# Set credentials of your KBase account. If you don't have one, 
# please visit http://kbase.us/sign-up-for-a-kbase-account/
# Get a test_token from the KBase website by clicking on "Account"
# and then the "Developer Tokens" tab.  Note that tokens expire
# after 3 months

## CI token generated <DATE>
kbase_endpoint=https://ci.kbase.us/services
test_token=<CI_TEST_TOKEN>
auth_service_url=https://ci.kbase.us/services/auth/api/legacy/KBase/Sessions/Login

## APPDEV token created <DATE>
#kbase_endpoint=https://appdev.kbase.us/services
#test_token=<APPDEV_TEST_TOKEN>
#auth_service_url=https://appdev.kbase.us/services/auth/api/legacy/KBase/Sessions/Login

## PROD token generated <DATE>
#kbase_endpoint=https://kbase.us/services
#test_token=<PROD_TEST_TOKEN>
#auth_service_url=https://kbase.us/services/auth/api/legacy/KBase/Sessions/Login

auth_service_url_allow_insecure=false
---------------------------------------------------------------------

