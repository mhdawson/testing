## Near-term

* Make a recommendation on use of timers in tests
  * Many flaky tests are due to arbitrary timers
  * This would be a good learning experience on getting buy-in from the project.

## Long-term

* Identify an overall strategy to approach the tactical issues below.

* Process around flaky tests:
  * Review any current motivators for people to fix tests
  * Propose new ones, if necessary

* Flaky Tests
  * Catalog
  * Case-by-case, fix or refer to others with expertise
  * Explore ways to make this more efficient such as:
    * Identify flaky tests faster (perhaps collaborate with Build WG)
    * Recruit/motivate others to help fix flaky tests

* Skipped tests
  * Catalog
  * What to do?

* Known issues
  * Catalog and add tests that should be in `known_issues` that aren't?
  * What, if anything, to do with tests once they are in `known_issues`?

* Document
  * What, if anything, needs improving in `test/README.md`?

* Create unit tests?

* Re-organize tests if current setup is unwieldy?

* Document best practices, get buy-in, and implement. 
  * Lint rules where appropriate.
  * Use of timeouts would probably be a good one to get some consensus on.

* Obsolete or neglected tests
  * What to do with them?
    * For example, `test/debug`

* Automated pull request acceptance tooling.
  * This doesn't fit into the Testing WG charter, but it's easy to see why we would be interested and would want to collaborate with another group working on this.

* Anything we can do to make tests faster? Is it worth it?

* Tooling
  * Probably need to prioritize:
    * stress testing in parallel?
    * CI results search, automation, data collection
    * Flaky test identification

* Miscellaneous
  * Do we want to do anything about `assert`?
  * Recruitment/onboarding?
    * good-first-contributions?
  * Multi-VM testing issues?
    * If we
