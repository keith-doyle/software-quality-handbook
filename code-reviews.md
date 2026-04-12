#  Code Review Research Notes

---

##  Source 1
**Title:** Code Review Best Practices  
**Author / Site:** Google  
**Link:** https://google.github.io/eng-practices/review/  

**Key Points:**
- Focus on improving code readability and maintainability  
- Keep changes small for easier reviews  
- Review for correctness, design, and clarity  
- Comments should be clear and actionable  

**Useful Theme:** Review quality and clarity  

---

##  Source 2
**Title:** Code Review Best Practices  
**Author / Site:** Atlassian  
**Link:** https://www.atlassian.com/agile/software-development/code-reviews  

**Key Points:**
- Reviews should happen quickly to avoid delays  
- Limit pull request size  
- Encourage team collaboration  
- Use tools to streamline the process  

**Useful Theme:** Speed and collaboration  

---

##  Source 3
**Title:** How to Write the Perfect Pull Request  
**Author / Site:** GitHub  
**Link:** https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/  

**Key Points:**
- Provide clear descriptions in pull requests  
- Keep changes focused and well-scoped  
- Make it easy for reviewers to understand context  
- Smaller PRs improve review quality  

**Useful Theme:** Pull request quality  

---

##  Source 4
**Title:** Best Practices for Peer Code Review  
**Author / Site:** SmartBear  
**Link:** https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/  

**Key Points:**
- Code reviews should be limited in size and time  
- Review fatigue reduces quality  
- Defect detection drops in large reviews  
- Structured reviews improve outcomes  

**Useful Theme:** Review effectiveness  

---

##  Source 5
**Title:** Scaling Code Review at Stripe  
**Author / Site:** Stripe  
**Link:** https://stripe.com/blog/codereview  

**Key Points:**
- Fast feedback loops improve development speed  
- Strong review culture improves consistency  
- Communication is key in reviews  
- Automation supports scalability  

**Useful Theme:** Team culture and scalability  

---

##  Common Themes (Grouped)

###  Pull Request Size
- Keep PRs small and focused  
- Large PRs reduce review quality  

---

###  Review Speed
- Reviews should be completed quickly  
- Delays create bottlenecks and slow development  

---

###  Feedback Style
- Feedback should be clear, constructive, and respectful  
- Reviews should improve code, not criticise developers  

---

###  Code Quality Focus
- Prioritise readability and maintainability  
- Avoid overly complex or clever solutions  

---

###  Automation
- Use tools such as:
  - Linters (e.g. ESLint)  
  - Formatters (e.g. Prettier)  
  - CI pipelines (automated tests on PRs)  
- Automation reduces manual review effort  

---

##  Bad Practices Mentioned Repeatedly

- Large pull requests that are difficult to review  
- Delayed reviews slowing down development  
- Approving without properly reviewing the code (“rubber stamping”)  
- Harsh or unclear feedback  
- Focusing too much on minor style issues instead of logic  

---

##  Good Practices Mentioned Repeatedly

- Keep pull requests small and manageable  
- Provide clear and constructive feedback  
- Review code within a short timeframe  
- Focus on readability and maintainability  
- Use automation tools for consistency  

---

##  Real-World Example (Bad Code Review)

A developer submits a large PR (1000+ lines).  
The reviewer quickly scans the code and approves it without fully understanding it.

Result:
- Bugs are missed  
- Code is hard to maintain  
- Issues appear in production  

 Lesson:  
Superficial reviews can be as harmful as no review at all  

---

##  What Makes a Good PR Description

A good pull request should include:
- Clear summary of what was changed  
- Reason for the change (why it’s needed)  
- Any important context for reviewers  
- Screenshots or examples (if relevant)  
- Notes on testing performed  

