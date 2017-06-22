\\\
var allBrowsers = [browsers.windows.edge,
                   browsers.windows.firefox,
                   browsers.osx.chrome,
                   browsers.osx.safari];
run.setPlatforms(allBrowsers);
\\\

### Checkout form
Ensure that a user can select a product and checkout successfully.

Steps:
1. Create an account or sign in to an existing account.
2. Select a product from the list of products.
3. Go to checkout page.

Validate:
- [ ] Price displays correctly.
- [ ] Taxes and fees are calculated correctly.
- [ ] Required fields are indicated.
- [ ] Correct messaging displays for field and payment errors.
- [ ] User can successfully check out once all fields are entered.
- [ ] User is taken to confirmation page.