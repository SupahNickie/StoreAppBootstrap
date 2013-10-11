RAILSCAST EPISODE 328

October 10, 2013

- Summary: Followed along with the episode mentioned above to create a basic Rails "store" app with responsive Bootstrap styling.

- ISSUES: The Railscast episode used both a different version of the Bootstrap gem (using LESS vs. the one I was using: SASS) as well as a different version number of Bootstrap (Railscast: 2.x vs Mine: 3.0), so some rearranging of HTML elements and renaming of classes needed to be worked out to fix the issues encountered while working with the Railscast.

- ERRORS: One error I noticed was that for some reason my server threw an error at me after I had put the computer in suspend mode and then rebooted the WEBrick server, claiming that the required file 'twitter/bootstrap' could not be found, even though I hadn't changed any of the code. I resolved the issue by swearing at the computer and then re-installing the gem with the command "gem install bootstrap-sass-rails" just to see if that did anything, then restarted the rails server, which did the trick!


Final Appearance

![Screencap](/public/images/screenshot.png "Screencap of Working Deployment")
