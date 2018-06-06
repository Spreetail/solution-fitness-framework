## Environment Awareness

Environment Awareness is the ability for a software system to detect in which environment (dev, staging, prod) it is currently running. This environment awareness is important when working with multiple versions of databases, as well as integrating with external services. For example, a solution may use a mocked version of an external API endpoint when running locally as a bandwidth consideration or as a way to isolate external services from noise from incomplete applications. 

*Acceptance Criteria* - Codebase has configuration that is dependent on the currently selected environment.   