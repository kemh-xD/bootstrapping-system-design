# `DESIGNING DATA INTENSIVE APPLICATION`
We call an application `data-intensive` if data management is one of the primary challenges developping the application

Such applications are typically built from standard building blocks that provide
commonly needed functionality. <br/>For example, many applications need to do the
following:
* Store data so that they, or another application, can find it again later (`databases`)
* Remember the result of an expensive operation, to speed up reads (`caches`)
* Allow users to search data by keyword or filter it in various ways (`search indexes`)
* Handle events and data changes as soon as they occur (`stream processing`)
* Periodically crunch a large amount of accumulated data (`batch processing`)

There are many database systems with different characteristics, suitable for different purposes.<br/>How do you choose which one to use? 
### We need to figure out which tools and which approach are appropriate and it's all about trade-offs
### `That's why we are here :)`