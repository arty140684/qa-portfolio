# WEB-01

## Title
Selected license (SCA) is not preserved when navigating from Italy 40 page to share pages

## Environment
- Website: capital.com
- License: SCA (UAE)
- Language: EN
- Browser: Chrome

## Steps to Reproduce
1. Open capital.com
2. Select SCA license (UAE)
3. Navigate to Markets → Indices
4. Open Italy 40 index page
5. Click on "Ferrari" link

## Expected Result
User is redirected to SCA version of the page:
https://capital.com/en-ae/...

## Actual Result
User is redirected to FCA version:
https://capital.com/en-gb/...

## Impact
Users are redirected to a different regulatory region, which may:
- display incorrect legal information
- violate regional compliance requirements
- create confusion for users

## Scope
Reproducible for multiple links:
- Ferrari
- Enel
- UniCredit
- ENI

## Notes
Issue appears to be related to incorrect routing or missing license parameter in links.
