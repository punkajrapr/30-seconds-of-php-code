# Contribution Guide

## Quick Guide
- Fork the repo.
- Checkout.
- Install the dependencies `composer install --dev`
- Generate your snippet using `php scripts/generate snippet` or `composer generate snippet` command.
- Update your snippet file located at snippets eg. `snippet/mySnippet.md`
- Add the function to `src/helpers.php`
- Write the test case.
- Test the code using `composer test`
- Make the pull request.

## Coding Style
We follows the PSR-2 coding standard.
