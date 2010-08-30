Errbit: The open source self-hosted error catcher
=================================================

Errbit is an open source, self-hosted error catcher. It is [Hoptoad](http://hoptoadapp.com) 
API compliant so you can just point the Hoptoad notifier at your Errbit server if you are 
already using Hoptoad.

Errbit may be a good fit for you if:

* Your exceptions may contain sensitive data that you don't want sitting on someone else's server
* Your application is behind a firewall
* You'd like to brand your error catcher
* You want to add customer features to your error catcher
* You're crazy and love managing servers

If this doesn't sound like you, you should probably stick with [Hoptoad](http://hoptoadapp.com).
The [Thoughtbot](http://thoughtbot.com) guys offer great support for it and it is much more worry-free.
They have a free package and even offer a *"Hoptoad behind your firewall"* solution.

Installation on Heroku
------------

  Edit seed.rb for the admin credentials.
  
            heroku create foo
            cd foo
            heroku addons:add mongohq:free
            git push heroku master


Special Thanks
--------------

* [Michael Parenteau](http://michaelparenteau.com) - For rocking the Errbit design and providing a great user experience.
* [Relevance](http://thinkrelevance.com) - For giving me Open-source Fridays to work on Errbit and all my awesome co-workers for giving feedback and inspiration.
* [Thoughtbot](http://thoughtbot.com) - For being great open-source advocates and setting the bar with [Hoptoad](http://hoptoadapp.com).

Contributing
------------
 
* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with Rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.

Copyright
---------

Copyright (c) 2010 Jared Pace. See LICENSE for details.
