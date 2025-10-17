---
name: "Pull Request"  
about: "Template changes, improvements, and repository updates"  
title: "PR: {short summary}"  
labels: ["status:needs-review"]  
---

# Pull Request

> This repository maintains AI templates following the [Template Specification](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md).
> All contributions should align with our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md).

## Summary

### What does this PR do?
<!-- Brief description of the changes -->

### Type of Change
- [ ] 📝 New template(s)
- [ ] 🔧 Template improvement(s)
- [ ] 📚 Documentation update
- [ ] 🐛 Bug fix
- [ ] 🚀 Feature enhancement
- [ ] 🔥 Breaking change
- [ ] 🧹 Maintenance/refactoring

## Linked Issues

<!--
List any related issues by number (e.g. closes #123, fixes #456, relates to #789).
Remove this section if no issues are linked.
-->

Closes #
Relates to #

## Templates Modified/Added

### New Templates
<!-- List new templates with their intended folder locations -->
- `/chatgpt/sales/email-outreach.md` - Cold email outreach template
- `/claude/support/bug-analysis.md` - Technical issue analysis template

### Modified Templates  
<!-- List existing templates that were changed -->
- `/gemini/development/code-review.md` - Added safety guidelines
- `/copilot/research/market-analysis.md` - Updated examples

### Removed Templates
<!-- List any templates that were removed and why -->
- `/outdated/old-template.md` - Replaced by improved version

## Template Quality Checklist

### Required Elements (for new/modified templates)
- [ ] Follows [Template Specification](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md)
- [ ] Includes complete front matter (title, model, use_case, status, version, author, last_updated)
- [ ] Contains all required sections (Goal, Inputs, Instructions, Quality Checks, Safety & Limits, Examples)
- [ ] Uses kebab-case naming convention
- [ ] Tested with target AI model
- [ ] Includes at least one complete example

### Content Quality
- [ ] Instructions are clear and unambiguous
- [ ] Safety guidelines are comprehensive
- [ ] Examples are realistic and helpful  
- [ ] Input requirements are well-defined
- [ ] Quality checks are measurable
- [ ] Appropriate for intended use case

### Testing Evidence
- **AI Model(s) Tested**: 
- **Test Date**: 
- **Sample Results**: [Link to test outputs or brief description]

## Impact Assessment

### Backward Compatibility
- [ ] No impact on existing templates
- [ ] Minor updates to existing templates
- [ ] Requires migration guide
- [ ] Breaking changes (requires major version bump)

### Documentation Impact
- [ ] No documentation changes needed
- [ ] README.md updated
- [ ] CONTRIBUTING.md updated
- [ ] New documentation added
- [ ] Help/example documentation updated

## Security & Safety Review

### Template Safety
- [ ] Templates include appropriate ethical boundaries
- [ ] No templates facilitate harmful activities
- [ ] Safety sections are comprehensive
- [ ] Privacy considerations addressed

### Repository Security
- [ ] No sensitive information exposed
- [ ] No malicious code or links
- [ ] Dependencies are secure (if any)

## Changelog

<!--
Required for release automation.
Format: Keep a Changelog.
Categories: Added, Changed, Fixed, Removed.
User-facing notes only. Use the `skip-changelog` label for internal-only changes.
-->

### Added
- New ChatGPT sales email template with personalization features
- Claude support ticket analysis template for technical issues

### Changed
- Improved examples in GitHub Copilot code review template
- Updated front matter format for better consistency

### Fixed
- Corrected broken links in Gemini research templates
- Fixed typos in Figma automation instructions

### Removed
- Outdated GPT-3 templates (replaced with GPT-4 versions)

<!--
If no user-facing changelog entry is needed, apply the skip-changelog label to this PR.
-->

## Review Checklist

### For Template Reviewers
- [ ] Template follows specification
- [ ] Content is high quality and useful
- [ ] Examples work as expected
- [ ] Safety guidelines are appropriate
- [ ] No ethical concerns
- [ ] Proper categorization and naming

### For Maintainers
- [ ] CI checks pass
- [ ] No merge conflicts
- [ ] Appropriate labels applied
- [ ] Changelog updated (or skip-changelog applied)
- [ ] Documentation is up to date
- [ ] Breaking changes are documented

## Additional Notes

### Implementation Details
<!-- Any technical details reviewers should know -->

### Testing Instructions
<!-- How should reviewers test this change? -->

### Follow-up Tasks
<!-- Any tasks that should happen after this PR is merged -->
- [ ] Update documentation site
- [ ] Create release notes
- [ ] Notify community
- [ ] Other: _______________

---

**Reviewer Guidelines**: Focus on template quality, safety, and adherence to specification. Test templates with their target AI models when possible.