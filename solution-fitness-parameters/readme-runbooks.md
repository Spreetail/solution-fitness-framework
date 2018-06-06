## Readme - Runbooks
Each solution needs links to associated runbooks to be used in the event of a system outage. Runbooks can be specific to the system itself, as some systems are complex enough to warrant their own runbook. It is important to link to the runbooks of underlying infrastructure that supports a system. For example, if an information system is heavily dependent on RabbitMQ messaging, then the solution needs to link the associated runbook in case of an emergency. 

Runbooks themselves provide little value to a repository. Runbooks need to be regularly tested through WarGames testing to ensure that they are up-to-date and contain enough detail to trouble-shoot real-world problems with systems. 

Runbooks are typically some of the last documentation that is created for an application. Runbooks are often created during or right after an outage event.