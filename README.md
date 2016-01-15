Dear GitHub,

You have done so much to grow the open source community and make it really
accessible to users. Somehow you have us chasing stars and filling up squares,
improving the world’s software in the process.

However, many of us are frustrated. Those of us who run some of the most popular
projects on GitHub feel completely ignored by you. We’ve gone through the only
support channel that you have given us either to receive an empty response or
even no response at all. We have no visibility into what has happened with our
requests, or whether GitHub is working on them. Since our own work is usually
done in the open and everyone has input into the process, it seems strange for
us to be in the dark about one of our most important project dependencies.

The problems we most frequently have, and our best ideas for how to address
them, are:

- Issues are often filed missing crucial information like reproduction steps or
  version tested. We’d like issues to gain custom fields, along with a mechanism
  (such as a mandatory issue template, perhaps powered by a newissue.md in root
  as a likely-simple solution) for ensuring they are filled out in every issue.
- Issues often accumulate content-less “+1” comments which serve only to spam
  the maintainers and any others subscribed to the issue. These +1s serve a
  valuable function in letting maintainers know how widespread an issue is, but
  their drawbacks are too great. We’d like issues to gain a first-class voting
  system, and for content-less comments like “+1” or “:+1:” or “me too” to
  trigger a warning and instructions on how to use the voting mechanism.

- Issues and pull requests are often created without any adherence to the
  CONTRIBUTING.md contribution guidelines, due to the inconspicuous nature of
  the “guidelines for contributing” link when creating an issue and the fact
  that it often contains a lot of information that isn’t relevant to opening
  issues (such as information about hacking on the project). Maintainers should
  be able to configure a file in the repo (interpreted as GFM) to be displayed
  at the top of the new issue / PR page instead of that link. Maintainers can
  choose to inline content there and / or link to other pages as appropriate.

Hopefully none of these are a surprise to you as we’ve told you them before.
We’ve waited years now for progress on any of them. If GitHub were open source
itself, we would be implementing these things ourselves as a community—we’re
very good at that!

Signed,

- Adam Bradley ([@adamdbradley](https://github.com/adamdbradley)), maintainer of Ionic
- Addy Osmani ([@addyosmani](https://github.com/addyosmani)), maintainer of TodoMVC
- Andreas Tolfsen ([@andreastt](https://github.com/andreastt)), maintainer of Selenium
- Ariya Hidayat ([@ariya](https://github.com/ariya)), maintainer of PhantomJS
- Ashley Williams ([@ashleygwilliams](https://github.com/ashleygwilliams)), Developer Community Manager, npm
- Ben Briggs ([@ben-eb](https://github.com/ben-eb)), maintainer of PostCSS
- Cătălin Mariș ([@alrra](https://github.com/alrra)), maintainer of HTML5 Boilerplate
- Christopher Chedeau ([@vjeux](https://github.com/vjeux)), maintainer of React Native
- Dave Methvin ([@dmethvin](https://github.com/dmethvin)), maintainer of jQuery
- Domenic Denicola ([@domenic](https://github.com/domenic)), maintainer of WHATWG Standards
- Feross Aboukhadijeh ([@feross](https://github.com/feross)), maintainer of WebTorrent
- Forbes Lindesay ([@ForbesLindesay](https://github.com/ForbesLindesay)) maintainer of Pug (formally known as Jade)
- Henry Zhu ([@hzoo](https://github.com/hzoo)), maintainer of JSCS
- Jack Humbert ([@jackhumbert](https://github.com/jackhumbert)), maintainer of QMK Firmware
- James Kyle ([@thejameskyle](https://github.com/thejameskyle)), maintainer of Babel
- John-David Dalton ([@jdalton](https://github.com/jdalton)), maintainer of Lodash
- Juriy Zaytsev ([@kangax](https://github.com/kangax)), maintainer of Fabric.js
- Ken Wheeler ([@kenwheeler](https://github.com/kenwheeler)), maintainer of Slick
- Kent C. Dodds ([@kentcdodds](https://github.com/kentcdodds)), maintainer of angular-formly
- Mario Zechner ([@badlogicgames](https://github.com/badlogic)), maintainer of libGDX
- Nicholas C. Zakas ([@nzakas](https://github.com/nzakas)), maintainer of ESLint
- Nicolás Bevacqua ([@bevacqua](https://github.com/bevacqua)), maintainer of `dragula`
- Pascal Hartig ([@passy](https://github.com/passy)), maintainer of TodoMVC
- Ricardo Cabello ([@mrdoob](https://github.com/mrdoob)), maintainer of three.js
- Ryan Cavanaugh ([@searyanc](https://github.com/RyanCavanaugh)), maintainer of TypeScript
- Sam Saccone ([@samccone](https://github.com/samccone)), maintainer of Marionette
- Sindre Sorhus ([@sindresorhus](https://github.com/sindresorhus)), maintainer of Yeoman
- Trek Glowacki ([@trek](https://github.com/trek)), a maintainer of Ember.js
- Sashko Stubailo ([@stubailo](https://github.com/trek)), a maintainer of Meteor
- Graeme Yeates ([@megawac](https://github.com/megawac)), a maintainer of Backbone and Underscore
- Chris Rebert ([@cvrebert](https://github.com/cvrebert)), a maintainer of Bootstrap

**Are you the maintainer of a project on GitHub and want to sign as well? Please open a pull request**

---

#### Scratchwork appendix:

**Frustrations:**

- Issue management and notifications do not scale for larger projects, they are
  overwhelming and it actively contributes to burnout of open source
  maintainers.
- No validation that any part of CONTRIBUTING.md has been adhered to before an
  issue is created
- Auto subscribing users when they get mentioned. This encourages random users
  to mention maintainers in issues wanting direct support leading to a lot of
  email noise.
- The existing pull request workflow and green “Merge” button encourage merge
  commits, which many larger projects do not allow.
- Excessive comment noise due to +1s and other nonsense interactions
- People adding “famous” people as contributor for fun to their projects,
  creating frustration for them and spam in the activity stream.

**Improvements:**

- Allow custom fields in issues (e.g. library version, language version,
  operating system)
- Make fields required (e.g. library version or link to a test case; making such
  information mandatory would dramatically reduce noise)
- Show contributing guidelines before opening an issue (yet another noise
  reduction)
- Show count of how many people will be notified next to the issue creation
  button
- View notifications without marking them as read
- Allow disabling automatically marking them as read, so they have to be
  manually marked as read.
- Flag notifications or issues for future follow up (i.e. create a
  personal/private flag)
- Turn unintuitive search query system into GUI
- Auto-search for "similar issues" based on the words in the issue title and
  body when the issue is created, to prevent dups - similar to how Stack
  Overflow already works
- Select multiple issues and then close with a single comment
- Ability to merge issues
- Ability to move issues to other repos
- Explicitly eliminate content-free replies like "+1", or convert them into a
  rating system for issues so watchers aren't constantly notified! A separate
  rating system would be nice too.
- Voting system for proposals
- Something that surfaces votes at an issue-viewing level that can be sorted
  easily by counts/labels. This allows distilling the highest priority bits to
  work on.
- Add support for custom reply messages (e.g. “Can’t reproduce...”, “Please
  attach a test case...”, “Please use forum for questions...”, etc.)
- Add support for default placeholder message when opening an issue (similar to
  what Google Code did — “What steps would reproduce a problem? … Expected
  result: … Actual result: … etc.”)
- Better tools for addressing tracker spam comments/issues
- Don’t make it so easy to submit bad PRs → For example, remove the default
  commit title when creating a commit from the GitHub UI. When I see “Update
  readme.md”, I know I’m in for annoyance.
- Ability to block users from an organization.
- Allow assigning issues to anyone who has contributed to the issue, not just
  project maintainers. This way issues can be assigned back to the OP when more
  info is needed.
- Support explicitly marking an issue/pull request as “Needs Revision”/”Needs
  More Info” and then have the tag automatically removed once someone comments
  on the issue/updates the code in the pull request.
- Support “private labels” for issues. Users should be able to add private
  labels to any issue, even if it’s a project they don’t maintain. They should
  then be able to use them for querying/filtering.
- Allow automation rules, such as automatically notifying or closing when issues
  have been untouched for a long time.
- Support linear histories in the big green merge button. The project maintainer
  should be able to specify whether merge commits should be created, or the
  change should be rebased on top of master.
- Support the ability to change the target branch in a PR without having to
  close and reopen a new one -- This way you do not have to lose the comments
  and discussion that may have happened in the original PR
- Allow more than one format for reviewing issues. For example, displaying all
  issues within a spreadsheet format, sortable by columns.
