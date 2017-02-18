# Hextet Systems - BGP Questionnaire #

Date (YYYY-MM-DD): 

1. Your AS number assigned by ARIN: 

2. Model of your BGP router: 

3. What is the memory capacity into your BGP router? 

4. Do you want a MD5 password for your BGP session? 

5. Do you want to receive our (and upstreams) BGP communities? 

6. Which IPv4 routes do you want to receive? (Please, select only one option)
+   [ ] Full Routes  ~ 600,000 routes
+   [ ] Full Routes + Default route  ~ 600,000 routes
+   [ ] Customer Routes + Default route  ~ 5 routes
+   [ ] Only default route
+   [ ] no IPv4 BGP session

7. Which IPv6 routes do you want to receive? (Please, select only one option)
+   [ ] Full Routes  ~ 30,000 routes
+   [ ] Full Routes + Default route  ~ 30,000 routes
+   [ ] Customer Routes + Default route  ~ 16 routes
+   [ ] Only default route
+   [ ] no IPv6 BGP session

8. Do you register your routes into an IRR? 
+   If yes, what is the AS-SET? 
+   If no, Hextet Systems will register your routes in your behalf in the ARIN IRR.

9. Which routes would you announce (IPv4 and IPv6)? If you want to announce more specific routes than ARIN assignation, please make two lists (one with ARIN assigned bloc and another with real announce routes).


Note: Hextet Systems will configure filter (prefix-list) on their BGP connections. So you shall absolutely communicate with our Network Operations Centre (noc@hextet.net) if you want to announce a new route, even if your routes are recorded in an IRR.
