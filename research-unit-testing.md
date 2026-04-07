# Research Notes – Unit Testing and Test Coverage

## Source 1
- **Title:** The Test Pyramid
- **Author / Site:** Martin Fowler
- **Link:** https://martinfowler.com/articles/practical-test-pyramid.html
- **Key points:**
  - Focus on many small unit tests
  - Avoid too many UI/integration tests
  - Tests should be fast and reliable
- **Useful theme:** Test structure

## Source 2
- **Title:** Unit Testing Best Practices
- **Author / Site:** Atlassian
- **Link:** https://www.atlassian.com/continuous-delivery/software-testing/unit-testing
- **Key points:**
  - Test edge cases and failures
  - Keep tests simple and readable
  - Tests should be independent
- **Useful theme:** Good test design

## Source 3
- **Title:** Common Unit Testing Mistakes
- **Author / Site:** Dev.to
- **Link:** https://dev.to
- **Key points:**
  - Only testing happy paths is a mistake
  - Ignoring failing tests reduces quality
  - Overcomplicated tests are hard to maintain
- **Useful theme:** Testing mistakes

## Source 4
- **Title:** What Makes a Good Unit Test?
- **Author / Site:** Google Testing Blog
- **Link:** https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html
- **Key points:**
  - Good tests should be fast and reliable
  - Tests should fail only when there is a real issue
  - Avoid flaky tests that randomly pass/fail
- **Useful theme:** Test reliability

## Source 5
- **Title:** Unit Testing Principles, Practices, and Patterns (Summary)
- **Author / Site:** Vladimir Khorikov (summary content)
- **Link:** https://enterprisecraftsmanship.com/posts/unit-testing-best-practices/
- **Key points:**
  - Tests should be simple and easy to understand
  - Tests should focus on behaviour, not implementation
  - Overly complex tests reduce maintainability
- **Useful theme:** Maintainable test design
---

## Common Themes
- Tests must cover edge cases, not just normal scenarios
- Tests should be simple, readable, and easy to maintain
- Reliable tests are critical (tests should not randomly fail)
- Unit tests should focus on behaviour rather than implementation details
- Fast and independent tests allow frequent execution

## Bad Practices Mentioned Repeatedly
- Only testing happy paths
- Ignoring failing tests
- Writing overly complex or fragile tests
- Creating flaky tests that give inconsistent results
- Focusing only on coverage percentage instead of test quality

## Good Practices Mentioned Repeatedly
- Test edge cases and error conditions
- Keep tests simple and readable
- Ensure tests are independent and reliable
- Run tests regularly during development
- Focus on meaningful test coverage rather than just high numbers