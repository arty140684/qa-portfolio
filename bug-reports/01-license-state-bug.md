# 01-license-state-bug.md

## Title
Inconsistent behavior of license selection after navigation and page reload

## Environment
- Website: capital.com
- License: SCA (UAE)
- Language: EN
- Browser: Chrome

## Preconditions
User has selected SCA license

## Steps to Reproduce
1. Open capital.com
2. Select SCA license (UAE)
3. Navigate to any market page (e.g., Indices → Italy 40)
4. Click any internal link (e.g., company or instrument)
5. Refresh the page

## Expected Result
Selected license (SCA) remains consistent across navigation and after page reload

## Actual Result
License may switch to a different region (e.g., FCA / en-gb) after navigation or page reload

## Impact
- Users may unknowingly switch to a different regulatory region
- Legal information and trading conditions may become incorrect
- Potential compliance risks for region-specific regulations
- Reduces user trust due to inconsistent behavior

## Scope
- Reproducible across multiple pages
- Affects navigation between instruments and markets

## Notes
Issue suggests that license state is not persistently stored (e.g., missing session/cookie handling or incorrect routing logic).

## Priority
High

## Severity
Major
