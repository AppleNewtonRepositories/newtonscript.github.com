# Contributing to NewtonScript.org

We welcome feedback, bug fixes, content & display improvements, and translations. Ultimately, what gets accepted and merged into the project is up to NewtonScript.org staff (specifically, [Morgan Aldridge](https://github.com/morgant), the current project maintainer), but you are encouraged to submit any suggestions.

Please submit errors/corrections, additions, and feature requests via the project’s [issue tracker](https://github.com/NewtonScript/newtonscript.github.com/issues).

## What You Need

You will need the following to contribute:

* A [GitHub](http://github.com) account for submitting pull requests
* A familiarity with HTML5
* Experience with CSS3 is a plus

## Making Changes

Follow these steps when making changes. That way, they will most likely be accepted with few headaches and very little back and forth.

1. Fork the [newtonscript.github.com](https://github.com/NewtonScript/newtonscript.github.com) project on GitHub.
2. Create a topic branch from the `master` branch. Name your branch appropriately, reflecting the intended changes. (e.g. “new-license”, “style-overhaul”, or “responsive-design-fixes”)
3. Make your edits (please try to conform to our [style guide](#style-guide)).
4. Make commits in logical units and with explanatory commit messages.
5. Preview your changes in an HTML5-capable web browser to ensure nothing is broken and everything is rendering correctly.

## Submitting Changes

When you’ve completed your changes and are ready to merge them into the main project, follow these steps to submit them for review.

1. Push the changes to your fork of the [newtonscript.github.com](https://github.com/NewtonScript/newtonscript.github.com) project on GitHub
2. Submit a pull request to the [newtonscript.github.com](https://github.com/NewtonScript/newtonscript.github.com) project

That’s all there is to it.

If you followed the “Making Changes” guidelines and the changes are aligned with the vision of the project, it should be a smooth process to merge them.

## Style Guide

### HTML

* Please write well-formed HTML to the HTML5 specification.
* Please write pretty HTML with proper indentation for nested elements.
* Please use tabs instead of spaces for indentation.

### Text

* Please alphabetize referenced materials (software, source code, reference documentation, etc.) by title and authors by last name.
* For sub lists which are more appropriately listed in chronological order (e.g. lists of publication issues), please do so.
* Please use [serial commas](https://en.wikipedia.org/wiki/Serial_comma).

### Resource Template

The following is the template used to list referenced resources (software, source code, documentation, etc.):

```html
<dt id="[RESOURCE-ANCHOR]"><a href="[RESOURCE URL]">[RESOURCE TITLE/NAME]</a></dt>
<dd>
	<p>[RESOURCE DESCRIPTION]</p>
	<ul class="metadata">
		<li>Author: <a href="[AUTHOR/ORGANIZATION URL]">[AUTHOR/ORGANIZATION NAME]</a></li>
		<li>Platform: [PLATFORM]</li>
		<li>License: [“Freeware”/”Shareware”/”Commercial”/”Open Source”]</li>
		<li>Format: [“TXT”/”HTML”/”PDF”/”Book”/”Magazine”/”Video”]</li>
		<li>Mirror: <a href="[MIRROR URL]">[MIRROR TITLE/NAME]</a></li>
	</ul>
</dd>
```

**Important:** Whenever you link to a resource or its mirror, please visit the [Internet Archive Wayback Machine](http://archive.org/web/) and submit that URL to “Save Page Now” to ensure its preservation!

Please reference the following descriptions of the fields from the above template, as well as existing examples on the site, when adding a referenced resource:

`RESOURCE-ANCHOR` — A unique anchor value for the reference. This accommodates direct linking to the reference. Optional.

`RESOURCE URL` — The URL for the referenced resource.

`RESOURCE TITLE/NAME` — The title or name of the referenced resource. This should be in proper title case, with the exception of software/source code where the project’s name itself may not be in proper title case. A common abbreviation for the resource title (e.g. “NTK”) may optionally be included).

`RESOURCE DESCRIPTION` — A short summary (one to three sentences) of the resource. For software, this should include its functionality and how NewtonScript comes into play. For reference material, it should describe what the documentation covers. For periodicals as a whole where individual issues or articles may also be available, it is suggested that those issues or articles be listed and linked individually following this section.

`AUTHOR/ORGANIZATION URL` — The URL to the author’s or organization’s site. Optional.

`AUTHOR/ORGANIZATION NAME` — The name of the person or organization that created or published the resource. Multiple names should be comma separated and placed in alphabetical order by last name. It is preferable to list all authors or the specific organization. In rare cases, it may be appropriate to use “Various” instead.

`PLATFORM` — The name of the platform which the resource was developed for. If multiple platforms are supported, they should be comma separated and in alphabetical order. For non-Newton platforms, the general platform type is suggested (e.g. “Mac OS”, “Mac OS X”, “Windows”, “Linux”, “BSD”, “BeOS”, etc.). For Newton platforms, the specific Newton OS version should be included (e.g. “Newton OS 1.x”, “Newton OS 2.x”, “Newton OS 2.1”, etc.) Optional, but should be included for software and source code. 

`LICENSE` — Optional, but should be included for software and source code.

`FORMAT` — The format which the documentation is available in. If multiple formats are available, they should be comma separated and may link directly to the specified format. Optional, but should be included for documentation.

`MIRROR URL` — The URL of an alternate source for the resource. Optional, but should be included whenever available.

`MIRROR TITLE/NAME` The name of an alternate source for the resource. Optional, but should be included whenever available.

