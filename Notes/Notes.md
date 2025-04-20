1. What is Temporal?
   In short, Temporal is a platform that guarantees the durable execution of your application code.
   It allows you to develop as if failures don't even exist.
   The Temporal platform handles these types of problems, allowing you to focus on the business logic, instead of writing application code to detect and recover from failures.

3. Workflows
   Temporal applications are built using an abstraction called Workflows.
   Temporal Workflows are resilient. They can run—and keeping running—for years, even if the underlying infrastructure fails.
   If the application itself crashes, Temporal will automatically recreate its pre-failure state so it can continue right where it left off.

4. Workflow is a Sequence of Steps. A flowchart in simple words.
   Real-time examples be like, interview-to-hire process. It takes weeks on one thread of application.

5. A workflow can contain Business logic that may take days, weeks, or longer to complete; Conditional statements; and Cycles (steps that refer to previous steps).
   
6. The only required component is a database, such as Apache Cassandra, PostgreSQL, or MySQL. The Temporal Cluster tracks the current state of every execution of your Workflows. It also maintains a history of all Events that occur during their executions, which it uses to reconstruct the current state in case of failure. It persists this and other information, such as details related to durable timers and queues, to the database.



