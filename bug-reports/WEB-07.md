# WEB-02

## Title
User is redirected to homepage after changing language on Help page

## Environment
- Website: capital.com
- License: SCA
- Browser: Chrome

## Steps to Reproduce
1. Open Help page
2. Scroll down
3. Change language (e.g., EN → AR)

## Expected Result
Current Help page reloads in selected language

## Actual Result
User is redirected to homepage

## Impact
- Disrupts user flow
- Forces user to manually navigate back to Help section
- Reduces usability of Help Center

## Notes
Navigation state is not preserved during language switch.
