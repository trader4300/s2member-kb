---
title: Testing in a Clean WordPress Installation
categories: tutorials
tags: troubleshooting
author: jaswsinc
github-issue: https://github.com/websharks/s2member-kb/issues/81
---

## Is it Really a Bug?

Here in the s2Member support department, we receive many bug reports that are difficult and/or impossible to reproduce on our side of things. A site owner will write to us and say, _"feature X is not working as expected"_. One of our support representatives will follow-up by testing that specific feature, but the problem doesn't exist on our side. Hmm... what gives? How can that be?

**Reason:** WordPress offers you lots of options! As a site owner you have the ability to mix s2Member with other plugins and a theme you like best. So the reason we are unable to reproduce the issue on our side? Your environment is slightly different than ours. Your WordPress installation has different plugins, it's had a different history, and it's probably running with a different theme too.

As you can imagine, testing every feature of s2Member with every possible combination of plugins, and with each and every theme that exists for WordPress — this is nearly impossible. **We need common ground! In fact, [our policy](https://wpsharks.com/support-policy) is that we require it :-)**

## Reproduce Problems in a Clean WordPress Environment

Like most WordPress plugins, s2Member was created, tested, and tuned on a default installation of WordPress. Therefore, we ask that you refrain from reporting a bug until you have been able to successfully reproduce the bug in a default installation of WordPress; i.e. an installation of WordPress where s2Member is the only plugin that has ever been installed; and one where you are using a default theme for WordPress (Twenty Sixteen, Twenty Fifteen, Twenty Fourteen, etc). If you’re using any [Must-Use Plugins](http://codex.wordpress.org/Must_Use_Plugins), please remember to deactivate those as well.

This will allow you to experience the intended behavior. If you find that the bug still exists, please [report it](http://github.com/websharks/s2member/issues/)! Most of the time though, bugs that exist in a live site cannot be reproduced once s2Member is isolated. This is an indication that there is a theme/plugin conflict on your live site.

Starting from a clean installation is key. If you start from a clean installation where s2Member behaves as expected, you can begin debugging your installation by adding one plugin and/or theme at a time, until you can successfully reproduce the issue; i.e., identify the conflicting plugin/theme.

## Getting Help with Theme/Plugin Conflicts

If you're integrating s2Member into a larger set of themes/plugins, we ask that you seek assistance from an experienced WordPress developer who can do a full review of your site and make the proper recommendations (e.g., helping you resolve conflicts between all plugins working together). If you followed the steps above, you should now have some idea of which plugin/theme combination is causing a problem for you. Please pass that information on to your developer.

See also: [Common Troubleshooting Tips](https://github.com/websharks/s2member-kb/issues/132)

## Our Support Policy

Support policy: <https://wpsharks.com/support-policy>

> We will not provide support and/or troubleshooting assistance for any Product which has been integrated with another 3rd-party theme or plugin. If you discover a bug, or an inconsistent behavior with a Product which is integrated into a mixture of other themes/plugins for WordPress, we ask that you start by disabling all other plugins and revert to the default theme for your current version of WordPress.

> If problems persist, even in a default theme for WordPress, and no other plugins are active, we are happy to help; please [open a new bug report here](http://github.com/websharks/s2member/issues/). Otherwise, if you are integrating our Products into a larger set of themes/plugins, we ask that you seek assistance from an experienced WordPress developer who can do a full review of your site and make the proper recommendations (e.g., helping you resolve conflicts between all plugins working together).

## How to Report Plugin/Theme Conflicts

If you identify a conflict between s2Member and another plugin, [we would love to hear about this](http://github.com/websharks/s2member/issues/)! While we cannot offer support for other 3rd-party themes/plugins, we do accept feedback. Theme/plugin conflicts are reviewed by our developers on a regular basis, and efforts to enhance compatibility are always underway. Thanks in advance for your patience!
