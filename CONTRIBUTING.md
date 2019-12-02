# Contributing guidelines

Thank you for your contribution, we really appreciate it.

The software world is complicated, describing the issue you are facing is not so easy, it's even harder to make everyone understand.

That's why these rules are set, and we do appreciate it if you can respect them.

Note that, rules are defined by human beings, it's flexible, but follow them does make both our lives better.

## File a bug

### Before submitting a bug report

Here is a checklist which may be very helpful, it even can solve your issue automatically sometimes :)

- [ ] I searched it on this repo, and there are no duplicated reports
- [ ] I searched it on the web, and there's no workaround
- [ ] I confirmed, it is most likely not a JavaScript issue, I cannot repro on other platforms
- [ ] I am using the latest version of JSBox, I installed it on the [App Store](https://apps.apple.com/us/app/id1312014438)
- [ ] I am not using a jailbroken iOS device, at least there are no tweaks that may be related

### Submitting a bug report

Thanks for your patient, now it's time to create a bug report, here are some suggestions:

- **Separate issues** - Don't describe two bugs in one report, it's hard to identify.
- **Describe it clearly** - Describe what the issue is, instead of "there's an issue".
  - Bad: "The app has a problem, I cannot use it."
  - Good: "console.log unable to handle arrays correctly, it generates unreadable strings."
- **Provide reproduce steps** - If we can reproduce the issue, it will be solved for sure.
- **Show me the code** - It's cool if you can provide some sample code, but keep in mind, we cannot review the entire project.
  - You can send the archive to us, or using [gist](http://gist.github.com/) for simple snippets
- **Minimize the repro** - The repro steps should be minimal, doesn't include any other information which might be misleading.
- **Expected result** - You may have a different option on a result, tell us your expected result.
  - E.g. It outputs "32", but I think it should be "42"
- **Environment** - It's recommended to attach system information, and the app version, etc.
  - E.g. iPhone 11 Pro Max, iOS 13.0, JSBox 1.56.0, App Store version

The philosophy is that the information should be **complete**, and not **misleading**. It's recommended to apply these rules to not only JSBox specific problems, but to all your questions :)

## Request a new feature

### Before submitting a feature request

We all love new features! That's that simple, but we still have a checklist that you can check:

- [ ] I searched it on this repo, and there are no duplicated reports
- [ ] I double-checked the [docs](https://docs.xteko.com/#/en/), confirmed it's not provided
- [ ] I searched it on the web, and there's no way to implement it with some APIs combined
- [ ] I believe it's not a feature that only benefits myself
- [ ] I believe it's legal, and compliant with the [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)

We know it's hard to confirm the last two, but keep in mind, if you know you are doing something that is not so decent, please don't :)

### Submitting a feature request

Similar to submitting a bug report, here are some rules:

- **Separate features** - Don't submit two features in one request.
- **Describe it clearly** - Describe how is the feature looks like, and why it is needed
- **Show me the code** - It's better to provide a sample code

For API changes, we'd really appreciate it if you can provide a sample code to describe your design. It's also interesting for you, because you are going to use it, isn't it?

## Search issues

You can search existing issues using some query patterns, such as this one:

[is:open is:issue label:bug](https://github.com/cyanzhong/jsbox-issues/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

Here is the label system we are using:

### Issue types

- **bug** - Confirmed bugs
- **enhancement** - Requests for enhancement/feature

### Issues components

- **jsbox** - Issues that related the JSBox app itself
- **builtin-modules** - Built-in modules, such as console, ui
- **3rd-party-modules** - 3rd party modules, such as lodash
- **documentation** - Improvements or additions to documentation

### Issue priorities

- **P0** - High priority, such as crashes, hangs
- **P1** - Medium priority, not so urgent but needs to be fixed
- **P2** - Low priority, nice to be fixed or implemented

Thanks for reading the guidelines, we really appreciate your contribution.