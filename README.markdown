### Rails Best Practices from the Book "Rails AntiPatterns"

#### General: Create modules/classes to isolate responsibilities for the models

1. Law of Demeter (delegation)
	* use delegation
2. Push all find() calls into finders on the model
	* use scopes or class methods
3. Keep finders on their own model
	* single responsibility principle kind of stuff
4. Delegate responsibility to new classes
5. Make use of modules
6. Reduce the size of large transaction blocks
	* use callbacks/filters
7. Use your active record associations and finders effectively
8. Learn and love the scope method
9. Use a full-text search engine
10. Extract into modules
11. Write a plugin
12. Make magic happen with metaprogramming
13. Simplify with simple flags
14. Denormalize into text fields
15. Make use of rails serialization
16. Learn about the view helpers that come with Rails
17. Add useful accessors to your models
18. Extract into custom helpers
19. Make use of rails helpers
20. Use haml
21. Use clearance/authlogic/devise
22. Use active record callbacks and setters
23. Move to a presenter
24. Store references instead of instances
25. Embrace REST
26. Refactor non-RESTful actions into a separate controller
27. Make use of nested resources
28. Use separate controllers for each nesting
29. Use rails 3 responders 
30. Set your timeouts
31. Move the task to the background
32. Use a gem
33. Obey the HTTP codes
34. Divide into confederated applications
35. Look for a gem first
36. Follow TAM
37. Prune irrelevant or unused gems
38. Consider vendored code sacrosanct
39. Make use of factories
40. Refactor into contexts
41. Watch your integration points
42. Tell, Don't Ask
43. Extract to a class method
44. Write normal unit tests without rails
45. Load only the parts of rails you need
46. Break out the atom bomb
47. Build to scale from the start
48. Make use of the system directory
49. Add indexes
50. Reassess your domain model
51. Don't do in Ruby what you can do in SQL
52. Move processing into background jobs
53. Never modify the up method on a committed migration
54. Never use external code in a migration
55. Always provide a down method in migrations
56. Eschew constraints in the database
57. Fail fast
58. Never fail quietly