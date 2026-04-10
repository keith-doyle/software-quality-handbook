# Unit Testing and Test Coverage

## Purpose of this section

Unit testing helps a startup catch problems early, reduce defects in production, and improve confidence when making changes to the codebase.

The purpose of this section is to define a practical approach to unit testing so that engineers write tests consistently and understand how to use test coverage in a useful way.

Unit testing should not be treated as a box-ticking exercise. It is a way to improve software quality, support safer changes, and reduce the cost of finding defects later in development.

---

## Why unit testing matters

Unit testing focuses on the smallest testable parts of a system, such as individual methods or functions.

It helps teams:
- detect defects early  
- verify that code behaves as expected  
- reduce the risk of regressions when code changes  
- improve confidence during development and refactoring  

In a startup environment, this matters because engineers often move quickly and make frequent changes. Without tests, even small changes can introduce defects that are difficult to detect until later.

Unit testing is also valuable because defects found earlier are generally easier and cheaper to fix than defects found later in production.

---

## Good practices to follow

### Test edge cases and error conditions

Tests should not only check normal inputs. They should also check:
- edge cases  
- boundary values  
- invalid input  
- expected error conditions  

For example, a calculator function may work correctly for `2 + 2 = 4`, but fail when given zero, negative numbers, or invalid values.

---

### Keep tests simple and readable

A good unit test should be easy to understand. If a test is too complicated, it becomes harder to maintain and less useful as documentation.

Simple tests make it easier to:
- understand what is being tested  
- identify the cause of failure  
- update tests when code changes  

---

### Keep tests fast and reliable

Unit tests should run quickly and give consistent results. A test that randomly passes or fails is unreliable and reduces trust in the test suite.

Reliable tests help developers run tests often and act on failures with confidence.

---

### Focus on behaviour, not implementation details

Tests should check what the code does, not just how it is written internally.

This makes tests more stable and less likely to break unnecessarily when the internal structure of the code changes but the behaviour remains correct.

---

### Run tests regularly

Unit tests are most effective when they are run regularly during development.

Running tests frequently helps teams:
- catch problems quickly  
- detect regressions early  
- avoid building more code on top of broken behaviour  

---

## Bad practices to avoid

### Only testing happy paths

A common mistake is writing tests only for normal scenarios. This creates a false sense of confidence because real systems often fail at boundaries and error conditions.

---

### Assuming high test coverage means high quality

High coverage does not automatically mean the tests are good.

A codebase can have high test coverage while still missing:
- meaningful assertions  
- edge cases  
- error-handling paths  
- realistic scenarios  

Coverage is useful, but it should be treated as an indicator rather than proof of quality.

---

### Writing overly complex tests

Tests should not be harder to understand than the code they are testing. Overly complex tests are difficult to maintain and are less likely to help the team.

---

### Ignoring failing tests

Failing tests should be investigated and resolved, not ignored. A failing test may indicate a real defect, a broken assumption, or a problem with the test itself.

---

### Creating flaky tests

Tests that pass and fail inconsistently damage trust in the test suite. Engineers may begin ignoring failures if they believe the tests are unreliable.

---

## Real-world issues teams face

One common issue is that teams write tests for obvious cases but forget edge cases.

For example, a method may work for standard input but fail when the input is empty, negative, or null. These cases are often where bugs appear.

Another issue is misunderstanding test coverage. A team may report high coverage and assume the system is well tested, even though the tests only cover basic scenarios and do not check meaningful outcomes.

This is why test quality matters more than simply aiming for a high percentage.

---

## Recommended company approach

At this company, unit testing should follow these rules:

- Unit tests must be written for important logic and behaviour  
- Tests must include normal cases, edge cases, and error conditions  
- Tests should be simple, readable, and reliable  
- Tests should focus on behaviour rather than internal implementation  
- Failing tests must be investigated and not ignored  
- Test coverage should be used as a guide, not as the only measure of test quality  

Following this approach will improve confidence in the codebase and reduce the number of defects that reach later stages of development.

---

## Further reading

- https://martinfowler.com/articles/practical-test-pyramid.html  
- https://www.atlassian.com/continuous-delivery/software-testing/unit-testing  
- https://dev.to  
- https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html  
- https://enterprisecraftsmanship.com/posts/unit-testing-best-practices/  