# Language Setting Guide for Sketchware

- [Language Setting Guide for Sketchware](#language-setting-guide-for-sketchware)
    - [Currently Available Language Files](#currently-available-language-files)
    - [How to Change the Language Setting for Sketchware](#how-to-change-the-language-setting-for-sketchware)
        - [Option 1: I already have downloaded the translated strings.xml file.](#option-1-i-already-have-downloaded-the-translated-stringsxml-file)
        - [Option 2: I don't have the strings.xml file, and I have to translate it.](#option-2-i-dont-have-the-stringsxml-file-and-i-have-to-translate-it)
    - [I Want to Contribute!](#i-want-to-contribute)
        - [Option 1: Language file exists inside this repository. I found an error or  want to improve it](#option-1-language-file-exists-inside-this-repository-i-found-an-error-or-want-to-improve-it)
        - [Option 2: Language file doesn't exist, I want to translate it](#option-2-language-file-doesnt-exist-i-want-to-translate-it)

## Currently Available Language Files

Languages currently avaiable in this repository

[English 🇺🇸](https://raw.githubusercontent.com/sketchware/strings.xml/master/strings_en.xml)

[Korean 🇰🇷](https://raw.githubusercontent.com/sketchware/strings.xml/master/strings_kr.xml)


Download Guide:

1. Click on the desired language file below
2. Right click on the page, and save it as `strings.xml` to your desired destination
![](https://github.com/sketchware/strings.xml/blob/master/screenshots/save_as.png)
3. Go to [How to Change the Language Settings for Sketchware](#how-to-change-the-language-setting-for-sketchware) step


## How to Change the Language Setting for Sketchware

### Option 1: I already have downloaded the translated strings.xml file.

If the file name is not `strings.xml`, rename the file from `strings_XX.xml` to `strings.xml`. (Note that `XX` in the file name can be any locale, en, kr...)

Copy and Paste the `strings.xml` file to `Device Storage -> sketchware -> localization`.

For me, I could find this folder under `sdcard/sketchware/localization` path, shown below:

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/localization.png)

Restart Sketchware, and you will see the message below:

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/patch_complete.png)

### Option 2: I don't have the strings.xml file, and I have to translate it.

Use your favorite File Manager to navigate to the following directory:

`Device storage -> sketchware -> localization`

There will be a string file, `strings_provided.xml`, provided to you in this directory.

For me, it was under `sdcard/sketchware/localization`, shown below:

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/localization.png)

Then, use your favorite text editor to open the `strings_provided.xml` file and translate it to your language.

After you're done modifying the string file, save it as `strings.xml`, and place it under the same directory as the `strings_provided.xml` file, which was under `.../sketcwhare/localization`.

When you restart Sketchware, you will see the message below:

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/patch_complete.png)

## I Want to Contribute!

Do you want to translate or improve Sketchware into your favorite language?

### Option 1: Language file exists inside this repository. I found an error or  want to improve it

If you have used GitHub before and are comfortable with using it, please fork this Repo, fix the errors, and send us a Pull request!

Else: 

1. Create a GitHub Account.

2. Click on the "Issues" tab on the top left corner of this repository.

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/issues.png)

3. Click on the "New Issue" button.

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/new_issues.png)

4. Please describe the error in the language file in this format:

Example: 

`Title: Revision needed for strings_en.xml`

`Comment: There is a typo on line 123. Sketchwaer -> Sketchware`

It should look something like this:

![](https://github.com/sketchware/strings.xml/blob/master/screenshots/issues_post.png)

5. Submit the issue and wait for us to fix the change! We will comment directly on the issue, letting you know that the fix has been applied.

### Option 2: Language file doesn't exist, I want to translate it

Please email the translated strings.xml file to [help@sketchware.io](mailto:help@sketchware.io). Please put [LANGUAGE] before the title, so we know that it's a request.

Title for Mail Example: `[LANGUAGE] Sketchware strings.xml for Hindi`

