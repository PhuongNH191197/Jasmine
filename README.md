# Jasmine
**CLASS : 
  -Class: Clock
      + Clock() :Jasmine's mock clock is used when testing time dependent code.
      + Constructor : new Clock()
       => Note: Do not construct this directly, Jasmine will make one during booting. You can get the current clock with jasmine.clock.
      + Methods : install() → {Clock} Install the mock clock over the built-in methods.
      + Returns: Type Clock
      + mockDate(initialDate opt) Date: Instruct the installed Clock to also mock the date returned by new Date()
      + tick(millis) int: Tick the Clock forward, running any enqueued timeouts along the way
      + uninstall() :   Uninstall the mock clock, returning the built-in methods to their places.
      + withMock(Function) : 
  -Class: Env (The Jasmine environment)
      + Constructor : new Env()
	  =>Note: Do not construct this directly, Jasmine will make one during booting.
	  + addReporter(reporterToAdd) :Add a custom reporter to the Jasmine environment.
	  + clearReporters() : Clear all registered reporters
	  + configuration() → {Configuration} : Get the current configuration for your jasmine environment
	  + configure(configuration) : Configure your jasmine environment
	  + hideDisabled() : 
	  + provideFallbackReporter(reporterToAdd) :Provide a fallback reporter if no other reporters have been specified.
	  + randomizeTests(value) : Set whether to randomize test execution order
	  + seed(value) : Set the random number seed for spec randomization
	  + stopOnSpecFailure(value) : Set whether to stop suite execution when a spec fails
	  + throwOnExpectationFailure(value) : Sets whether Jasmine should throw an Error when an expectation fails. This causes a spec to only have one expectation failure.	
  -Class: jsApiReporter
   	  + jsApiReporter : Reporter added by default in boot.js to record results for retrieval in javascript code. An instance is made available as jsApiReporter on the global object.




















    







