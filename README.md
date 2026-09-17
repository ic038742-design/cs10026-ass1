# Assignment 1 - plain HTML forms

These are the contribution and enquiry form interfaces for Assignment 1, in plain HTML with native browser validation.

## Open

Open `contribute.html` or `enquiry.html` in a browser. Use the links at the top to move between the forms.

The files work directly from your computer. Submit validates the required fields and reloads the same HTML page, with the entered values in the URL. Use sample values for your teacher's demonstration. The photo control lets you select files; photo contents are not uploaded. This is a static interface demonstration.

## Contribution form

- Contributor name: required text, maximum 25 alphabetical characters.
- Plant name: required text, maximum 25 alphabetical characters.
- Photo(s): required file input with multiple selection.
- Comments: required textarea with rows and columns.
- Submit and Reset buttons.

## Enquiry form

- First name and last name: required text, maximum 25 alphabetical characters each.
- Email address: required email input.
- Phone number: required tel input, maximum 10 digits, with a placeholder.
- Enquiry topic: required dropdown for families, genera or species.
- Comments: required textarea with rows and columns.
- Submit and Reset buttons.

Both name patterns use `[A-Za-z]{1,25}` to follow the alphabetical-only restriction. The phone pattern uses `[0-9]{1,10}`. Every control has a label, and related fields use fieldsets and legends.

## Demonstrate to your teacher

1. Press Submit with a form empty. The browser should block submission.
2. Try digits in a name field. Submission should be blocked.
3. Type 25 letters in either name field; a 26th letter cannot be typed.
4. On the enquiry form, test an invalid email and a phone containing letters. Submission should be blocked.
5. Leave the enquiry topic or comments empty. Submission should be blocked.
6. On the contribution form, leave photos empty. Submission should be blocked.
7. Fill a form using sample values and press Reset. The fields should clear; the enquiry dropdown returns to its prompt.
8. Fill the enquiry form with Aina, Tan, student@example.com, 0123456789, Plant families, and a comment. Submit should reload the same enquiry page after validation.

Replace the author placeholder with your own name before showing your source code.

## Package

- `contribute.html`
- `enquiry.html`
- `README.md`

The package contains the Assignment 1 form interfaces only, with no CSS decoration or JavaScript.
