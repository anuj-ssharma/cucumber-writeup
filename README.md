What is BDD

In a more top-down approach to software development, requirements passed down from business to the teams to translate them into working software. In the BDD approach, instead of a business stakeholder passing requirements to the development team, the developer and stakeholder collaborate to write requirements that express the outcome that the stakeholder wants. These requirements are initially written down as tests (aka Acceptance tests) and then through continuous feedback they are refined and updated.

Obviously, the test will fail as no code has been written yet. These tests are different from unit tests which ensure 'build the thing right' whereas acceptance tests are 'build the right thing'
This is pretty much the core concept of BDD. Writing acceptance tests first so that the right thing can be built. However, this relies heavily on collaboration between the teams and the stakeholders.

What is Cucumber

This is where cucumber comes in. Cucumber is a
- collaboration tool -
- test automation tool.

Cucumber was designed specially to help business stakeholders get involved in writing acceptance tests

How does cucumber work as a test automation tool

-> Reads specifications defined in feature files
-> Reads scenarios to test
-> Runs scenarios against the application


Scenario is made up steps which are written in the gherkin syntax. Corresponding stepdefs are written which can then be executed by cucumber.




Example
As a customer service representative,
