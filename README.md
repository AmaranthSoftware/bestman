# BestMan
He is better than any man. He is Best Man!

# Introduction
In the SOA world smallest atomic unit is a service. 
And thanks to REST arch, the communication is pretty much standardized, such that it can be abstracted out for common usage.

My current thoughts are around creating a git or db backedend that could used to drive test cases for a service.

# Usecases
-  Vanilla request response
-  Parameterized request response
-  Response validation with json-path
-  Delta based response validation

# Features
- [P1]  Executing request
    + [P2] Executing list of request
- [P2] Parameterized substitution in request
    + [P3] Chained request execution
    + [P2] Response validation
- [P1] Exists validation
- [P2] JsonPath validation
- [P3] Dynamic validation (running a snippet on piece of response)
    + [P3] Sourcing requests from repository git
- [P4] Plugin to source requests
    + [P4] UI
    + [p4] Delta testing
    + [p4] Writing validation+response to repository git
    + [p5] Writing validation+response to DB
- Communication integrations 
    + [p5] Github integration
    + [p6] Slack integration
    + [p6] Jenkins integration
    + [p5] Email integration


