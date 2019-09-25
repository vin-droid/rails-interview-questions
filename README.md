
# Rails Interview questions

**lntro:** 
Currently, I am searching for a job as a ruby on rails developer, I had many interviews and still going on hunting. I hope when you will be on the same track, these question will definitely help you to prepare for rails interview.  If you find some new question please comment here. For now I am adding just a list of questions but next, I will add solutions and links too.

Mostly Interviewer asks whatever you have mentioned in your resume/cv:
- **about your project**
- **about your role in that project**
- **gems which you used in the project**

Apart from your project's challenges, gems they asked the following questions.
- **Diff btw [delete_all and destroy_all](https://blog.revathskumar.com/2012/04/ruby-activerecord-difference-between.html), [delete and destroy](https://stackoverflow.com/questions/22757450/difference-between-destroy-and-delete?source=post_page-----8cb4db6aa660----------------------)** 
- **[Dirty methods](https://api.rubyonrails.org/classes/ActiveModel/Dirty.html)**
- **[How to delete local git branch](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely#targetText=Simply%20do%20git%20push%20origin,local%20branch%20ONLY!...)**
- **Diff [Module vs Class](http://rubylearning.com/satishtalim/modules_mixins.html#targetText=Ruby%20Modules%20are%20similar%20to,place%20of%20the%20class%20keyword.)**
- **[Mixin](https://www.sitepoint.com/ruby-mixins-2/) [more](https://ruby-doc.com/docs/ProgrammingRuby/html/tut_modules.html)**
- **[Working of CSRF token](https://medium.com/@charithra/introduction-to-csrf-a329badfca49)**
- **[Where CSRF token is stored.](https://stackoverflow.com/questions/20504846/why-is-it-common-to-put-csrf-prevention-tokens-in-cookies#targetText=Page%20loads%20in%20browser%2C%20then,field%20matches%20session%20stored%20token.) [more](https://cloudunder.io/blog/csrf-token)**
- **[Web server vs app server](https://hanumakanth.wordpress.com/2012/09/04/web-server-vs-application-server-rails/#targetText=Application%20server%20answers%20requests%20to,protocols%20like%20FastCGI%20or%20HTTP.) [more](https://medium.com/@yutafujii_59175/web-server-and-application-server-e984bf5f60af)**
- **[Deployment tools](https://hashnode.com/post/what-is-your-deployment-strategy-for-rails-app-what-tools-do-you-use-ciliz2xn7022dun533wx5l0ew) [link 2](https://hashnode.com/post/what-is-your-deployment-strategy-for-rails-app-what-tools-do-you-use-ciliz2xn7022dun533wx5l0ew) [link 3](https://www.airpair.com/ruby-on-rails/continuous-deployment)**
- **[Tools vs plugin vs gems vs Engine](https://stackoverflow.com/questions/23118472/gem-vs-plugin-vs-engine-in-ruby-on-rails)**
- **[How to create a gem](https://bundler.io/v2.0/guides/creating_gem.html) [more](https://guides.rubygems.org/make-your-own-gem/)**
- **[How to run an application without DB.](https://stackoverflow.com/questions/821251/how-to-configure-ruby-on-rails-with-no-database)**
- **What was the most difficult task which you faced and how to manage?**
- **[Git fancy](https://github.com/diogocavilha/fancy-git)**
- **Which frameworks are using ruby besides rails?**
- **Why we say ‘Ruby on Rails’ not ‘Rails on the ruby.**
- **Filter,callbacks,hooks,scopes,proc,lambda**
- **How to do metaprogramming in ruby.**
- **Jobs**
- **Rake tasks**
- **Benchmarking**
- **How to improve the performance of your website.**
- **What will be cases of taking time to load a website.**
- **Sorting programs from scratch.**
- **Have you worked open-sourced?**
- **Have you created a gem?**
- **List out gems which you used ever and why**
- **How a refund service works in Braintree.**
- **About action cable, live chat**
- **Git rebase vs Git merge**
- **Active records, action dispatch**
- **What is Serialization, why we prefer, how to use it?**
- **Which gem you use for the management  of roles of the user.**
- **Have you use angular or ember ever , how.**
- **How to do if you have some uncommitted code and need to take pull from the latest branch.**
- **How to push code when you reset the last commit in your local branch.**
- **What is git, commit, head, stash.**
- **How stash works.**
- **Which is the latest version of rails and ruby (stable and latest release)?**
- **Have you worked with Nginx?**
- **Have you used CSS/HTML, the latest version of HTML, CSS and why you used that version**
- **How much you are rating yourself on rails/ruby/javascript/jquery/UI**
- **Tell me 10 functions of jquery which you used in the project.**
- **Jquery vs javascript**
- **What are callbacks in JavaScript?**
- **Have you used the application only API?**
- **What is nil**
- **Nil vs FALSE**
- **Lazy Loding in Rails** [read](https://rubyinrails.com/2014/01/08/what-is-lazy-loading-in-rails/)
- **How to make a hash so that it returns the same result like hash[:name] and hash["name"] has an equal result.**
- **map /each/collect**
- **When ‘includes’ gives poor performance.**
- **Scope vs class methods.**
- **ORM**
- **What can be security leaks in your rails application?**
- **Versioning in API why should we use.**
- **What is caching(type), have you used.**
- **Routes (types, when and which preferable, versioning, put/patch, match, module, a single route for a resource, resources/resource.)**
- **When we should use join instead of includes.**
- **Association: all types / how to use polymorphic.**
- **How to use ransack for searching across multiple models like search by book, search by post.**
- **Social authentication.**
- **Authentication vs authorization.**
- **Which API of google have you used?**
- **Have you used country_select gem, how to do it from scratch?**
- **What is counter cache**
- **Concept Of STI (Single Table Inheritance)**
- **The sequence of the files executed when starts rails server.**
- **Why doctype is used in HTML?**
- **Difference between on and live (jQUERY)?**
- **Polymorphic association and its use?**
- **What is fingerprint in rails application(assets pipeline) ?.**
- **What are sockets?**
- **What is the Master-slave concept of active record?**
- **What are the Security Measures in rails?**
- **Make an SQL query to get the second-highest value from the record?**
- **How can we store sessions in rails and share session across multiple domains?**
- **What hidden fields are generated automatically in form_for.**
- **How to manage to store data in a single table if :**
 ```
                  Category  has_many sub_category
                  SubCategory has_many sub_type_catergory
                  Sub_type_category has_many ……………….
                  ...………………………………………………..
                  ...…………………………………………..n number category.
 ```
- **What major changes/new comes in rails 5.**
- **What major changes/new comes in rails 6.**
- **How to design bit.ly shorten url application? routes, logic, performance?**
- **Ruby method lookup path.**
- **Explain what singleton methods are. What is Eigenclass in Ruby?**
- **What is the difference between Proc and lambda?**
- **What are the three levels of method access control for classes and what do they signify?**
- **What is Rack?**
- **Explain the Rack application interface.**
- **Write a simple Rack application.**
- **How does Rack middleware works?**
- **What is ActiveJob? When should we use it?**
- **What is Asset Pipeline?**
- **Can you give me some examples of your favorite gems besides Ruby on Rails?**
- **What is a Rails engine?**
- **Describe types of associations in Active Record.**
- **What is Scopes? How should you**
- **Explain the difference between optimistic and pessimistic locking. use it?**
- **Explain what is a sessions mechanism. How does it work?**
- **Describe cross-site request forgery, cross-site scripting, session hijacking, and session fixation attacks.**
- **What is the difference between SQL Injection and CSS Injection?**
- **What are your favorite tools to find code smells and potential bugs?**
- **Why should you avoid fat controllers?**
- **Why should you avoid fat models?**
- **Explain extract Value, Service, Form, View, Query, and Policy Objects techniques.**
- **What is unit testing (in classical terms)?**
- **What is the primary technique for writing a test?**
- **What are your favorite tools for writing unit tests?**
- **What are your favorite tools for writing feature tests?**
- **How rails migration works? the process due to which it show how many migrations are pending and how many has been deleted**
- **How JWT token works. When it is preferable to use JWT**
- **What callbacks in  ActiveJobs**




