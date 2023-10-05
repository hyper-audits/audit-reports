# Security review process guide

## Questions to project

1. What is the clear scope (`.sol` files) of the security review?
2. Does the project have well written specifications & code documentation?
3. What is the code coverage percentage?
4. Are there any protocols that are similar to yours, which are they?
5. Have you had any audits so far, are you planning to do other audits/security programs as well?
6. Threat Model interview

Based on the answers we can discuss the effort needed, the payment amount and the timeline.

## Security review result & fixes review

After the time agreed upon has passed, the project will receive the security review report. The project has 7 days to apply fixes on issues found. Each issues should be fixed in a separate commit that has a message pointing to the issue being fixed. Then, a single iteration of a "fixes review" will be executed, free of additional charge, to verify the fixes are correct and secure.

### Important notes for the fixes review

- for any questions or clarifications on the vulnerabilities/recommendations in the report, you can reach out to me on the intended channel of communication.
- changes to be reviewed should not include anything else other than fixes for the reported issues, so no big refactorings, new features or architectural changes.
- in the case that fixes are too difficult to implement or more than one iteration of reviews is needed then this is a special case that can be discussed independently of this review.
