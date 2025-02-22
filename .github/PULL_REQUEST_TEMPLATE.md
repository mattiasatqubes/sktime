<!--
Thanks for contributing a pull request! Please ensure you have taken a look
at our contribution guide: https://github.com/sktime/sktime/blob/main/CONTRIBUTING.md
-->

#### Reference Issues/PRs
<!--
Example: Fixes #1234. See also #3456.

Please use keywords (e.g., Fixes) to create link to the issues or pull requests
you resolved, so that they will automatically be closed when your pull request
is merged. See https://github.com/blog/1506-closing-issues-via-pull-requests
-->


#### What does this implement/fix? Explain your changes.
<!--
A clear and concise description of what you have implemented.
-->

#### Does your contribution introduce a new dependency? If yes, which one?

<!--
If your contribution does add a new hard dependency, we may suggest to initially develop your contribution in a separate companion package in https://github.com/sktime/ to keep external dependencies of the core sktime package to a minimum.
-->

#### What should a reviewer concentrate their feedback on?

<!-- This section is particularly useful if you have a pull request that is still in development. You can guide the reviews to focus on the parts that are ready for their comments. We suggest using bullets (indicated by * or -) and filled checkboxes [x] here -->

#### Did you add any tests for the change?

<!-- This section is useful if you have added a test in addition to the existing ones. This will ensure that further changes to these files won't introduce the same kind of bug. It is considered good practice to add tests with newly added code to enforce the fact that the code actually works. This will reduce the chance of introducing logical bugs.
-->

#### Any other comments?
<!--
Please be aware that we are a loose team of volunteers so patience is necessary; assistance handling other issues is very welcome. We value all user contributions, no matter how minor they are. If we are slow to review, either the pull request needs some benchmarking, tinkering, convincing, etc. or more likely the reviewers are simply busy. In either case, we ask for your understanding during the review process.
-->

#### PR checklist
<!--
Please go through the checklist below. Please feel free to remove points if they are not applicable.
-->

##### For all contributions
- [ ] I've added myself to the [list of contributors](https://github.com/sktime/sktime/blob/main/CONTRIBUTORS.md) with any new badges I've earned :-)
  How to: add yourself to the [all-contributors file](https://github.com/sktime/sktime/blob/main/.all-contributorsrc) in the `sktime` root directory (not the `CONTRIBUTORS.md`). Common badges: `code` - fixing a bug, or adding code logic. `doc` - writing or improving documentation or docstrings. `bug` - reporting or diagnosing a bug (get this plus `code` if you also fixed the bug in the PR).`maintenance` - CI, test framework, release.
  See here for [full badge reference](https://allcontributors.org/docs/en/emoji-key)
- [ ] Optionally, I've added myself and possibly others to the [CODEOWNERS](https://github.com/sktime/sktime/blob/main/CODEOWNERS) file - do this if you want to become the owner or maintainer of an estimator you added.
  See here for further details on the [algorithm maintainer role](https://www.sktime.net/en/latest/get_involved/governance.html#algorithm-maintainers).
- [ ] The PR title starts with either [ENH], [MNT], [DOC], or [BUG]. [BUG] - bugfix, [MNT] - CI, test framework, [ENH] - adding or improving code, [DOC] - writing or improving documentation or docstrings.

##### For new estimators
- [ ] I've added the estimator to the API reference - in `docs/source/api_reference/taskname.rst`, follow the pattern.
- [ ] I've added one or more illustrative usage examples to the docstring, in a pydocstyle compliant `Examples` section.
- [ ] If the estimator relies on a soft dependency, I've set the `python_dependencies` tag and ensured
  dependency isolation, see the [estimator dependencies guide](https://www.sktime.net/en/latest/developer_guide/dependencies.html#adding-a-soft-dependency).


<!--
Thanks for contributing!
-->
