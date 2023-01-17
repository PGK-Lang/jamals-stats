# CRUD Implementation
> CRUD stands for **create, read, update, and delete** and acts as a way of integrating frontend design and backend data processing.  <br />

Within our project, we implement CRUD within each of our indivudal features in order to ensure a user-friendly and cohesive frontend design.

# Issues we overcame
 - Formatting
   - Changing the styles locally would sometimes be overridden by the default SASS. We resolved this issue by first editting any redundant styling within the [_sass](https://github.com/PGK-Lang/jamals-stats/tree/master/_sass) folder. Then we moved all local styling done within a style tag into the main.scss file. This allowed us to access sass variables and change the styling of elements and classes used in multiple places.
   - Centering items manually through use of percnt margins was often unreliable and very difficult to fine-tune. We learned how flex-boxes work with css and how they're used to organize elements within a container.
 - Navigation
   - Within the _config.yml, the baseurl was incorrectly set so when we clicked buttons in the nav bar, it would not be routed correctly. We first tried editting the layout of the nav bar to manually set each one where we were able to locate thea thte usse was the site.baseurl variable.

| Code code code |
| --- |
| [Rohin's design](https://pgk-lang.github.io/jamals-stats/drivers/) |
| [Ryan's design](https://pgk-lang.github.io/jamals-stats/sign-up/) |
| [Advays Design](https://pgk-lang.github.io/jamals-stats/sign-up/) |
| [Varalu's Design](https://pgk-lang.github.io/jamals-stats/Game-Technical/) |
