# testing

### Manual Testing
#### Features Working Correctly (in various screen sizes) Check

1. Navbar (Desktop):

    Unregistered user:
    - TEST 1.1 - _Anaconda MAA_ logo links to the _Home_ page - YES
    - TEST 1.2 - _About_ link goes to _About_ page - YES
    - TEST 1.3 - _Classes_ link goes to _Classes_ page - YES
    - TEST 1.4 - _Shop_ link goes to _Shop_ page - YES
    - TEST 1.5 - _Contact_ link goes to _Contact_ page - YES
    - TEST 1.6 - "Shopping bag amount in Euros" link goes to _Shopping Bag_ page - YES
    - TEST 1.7 - "Shopping bag amount in Euros" link stays white when _Shopping Bag_ is empty and becomes blue when there is at least one item in the _Shopping Bag_ - YES
    - TEST 1.8 - "Shopping bag amount in Euros" link value always reflects the actual total value of the _Shopping Bag_ - YES
    - TEST 1.9 - _Join Now_ link goes to _Memberships_ page - YES
    - TEST 1.10 - _Account_ button submenu shows only _Login_ and _Sign up_ links to non-registered (not logged in) users - YES
    - TEST 1.11 - _Sign up_ link under _Accounts_ button (not logged in user) links to _Sign Up_ page - YES
    - TEST 1.12 - _Login_ link under _Accounts_ button (not logged in user) links to _Sign In_ page - YES

    Registered user:

    - TEST 1.13 - _Account_ button submenu shows only _My Profile_ and _Logout_ links to registered (and logged in) users - YES
    - TEST 1.14 - User icon appears above _Account_ button when user is logged in and disappears when user logged out - YES
     - TEST 1.15 - _My Profile_ link under _Accounts_ button (registered user) links to _My Profile_ page - YES
     - TEST 1.16 - _Logout_ link under _Accounts_ button (registered user) links to _Sign Out_ page - YES

    Admin user:

    - TEST 1.17 - _Account_ button submenu shows _Products_, _Memberships_, _Classes_, _My Profile_ and _Logout_ links to (logged in) admin users - YES
    - TEST 1.18 - _Products_ link under _Accounts_ button (admin user) links to _Add Product_ page - YES
    - TEST 1.19 - _Memberships_ link under _Accounts_ button (admin user) links to _Add Membership_ page - YES
    - TEST 1.20 - _Classes_ link under _Accounts_ button (admin user) links to _Add Class_ page - YES

&nbsp;

2. Navbar (Mobile):
	- TEST 2.1 - _Recipes_ link goes to _Recipes_ page - YES
	- TEST 2.2 - _My Recipes_ link goes to _My Recipes_ page - YES
	- TEST 2.3 - _Add Recipe_ link goes to _Add Recipe_ page - YES
	- TEST 2.4 - _Categories_ link goes to _Categories_ page - YES
	- TEST 2.5 - _Sign up_ link goes to _Sign up_ page - YES
	- TEST 2.6 - _Log in_ link goes to _Log in_ page - YES
	- TEST 2.7 - _Log out_ logs user in session out of the session and redirects user to the _Log in_ page - YES
	- TEST 2.8 - Non-registered user can see only: _Recipe_, _Sign_up_ and _Log in_ navbar links - YES
	- TEST 2.9 - Registered user can see: _Recipe_, _My Recipes_, _Add Recipe_ and _Log out_ navbar links - YES
	- TEST 2.10 - Admin user can see: _Recipe_, _My Recipes_, _Add Recipe_, _Categories_ and _Log out_ navbar links - YES

&nbsp;