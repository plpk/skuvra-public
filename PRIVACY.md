# Skuvra Privacy Statement

Last updated: 2026-05-28

Skuvra is designed as a local-first Windows cleanup and maintenance utility.
Current official app releases do not include in-app telemetry, in-app
analytics, advertising, tracking SDKs, remote accounts, cloud sync, or automatic
upload of scan results.

This statement describes the current intended privacy behavior of official
Skuvra releases.

## What Skuvra Scans Locally

Depending on the feature you run, Skuvra may inspect local information such as:

- file paths, file sizes, timestamps, and cleanup categories for temporary files
  and duplicate-file scans;
- browser profile names, browser data categories, paths, and sizes for supported
  Chrome, Edge, Brave, Opera, and Firefox profiles;
- startup entry names, commands, paths, registry locations, and whether targets
  appear to exist;
- installed app names, versions, publishers, and uninstall commands;
- browser extension names, IDs, versions, profile names, and install paths;
- running process names, process IDs, memory usage, and CPU time;
- Windows access status, drive information, winget availability, and update-tool
  output; and
- Skuvra settings, scheduled-cleaning status, backup paths, and cleanup results.

Skuvra shows this information locally so you can review it before choosing an
action.

## Browser Data Handling

Skuvra may detect browser data files such as cache, cookies, history/download
database files, and form-data database files so it can show their paths,
categories, profile names, and sizes.

Skuvra should not read, print, export, summarize, transmit, or display the
contents of passwords, cookies, tokens, credential stores, browsing history,
download history, form values, or other browser secrets. Browser cleanup should
operate on selected files or folders as cleanup targets, not on extracted secret
values.

## What Skuvra Stores Locally

Skuvra may create local files under:

```text
%LOCALAPPDATA%\Skuvra
```

Current local storage includes:

- `settings.json` for Skuvra settings;
- `logs\` for scheduled-cleaning results; and
- `backups\` for supported startup or registry backups.

These files remain on your PC unless you remove them or Skuvra later adds a
clear cleanup option for them.

## Network Activity

Current official releases do not send Skuvra telemetry or analytics to the
copyright holder.

Some features invoke Windows or Microsoft-provided tools that may use the
network independently of Skuvra, including:

- `winget` for update scans and app updates;
- Windows Update settings and update commands;
- official uninstallers or installers launched by third-party apps; and
- GitHub or website links you choose to open outside the app.

Those tools and services may have their own privacy behavior, prompts, logs, and
terms.

## Public Website Analytics

The public website at `https://www.skuvra.com` uses Cloudflare Web Analytics to
measure basic site usage and page performance for the website. This website
analytics is separate from the Windows app. It is not used to collect Skuvra
scan results, cleanup selections, local file paths, browser profile contents,
passwords, cookies, tokens, or other local app data.

## No Sale of Personal Information

Current official releases do not sell personal information and do not share
Skuvra scan results with advertisers, data brokers, or analytics providers.

## Security Reports

If you find a privacy or security issue, please follow SECURITY.md. Do not post
private secrets, cookies, tokens, browsing contents, or exploit details in a
public issue.

## Future Changes

If the Windows app later adds telemetry, crash reporting, cloud features,
accounts, update checks controlled by Skuvra, or other networked data
collection, this privacy statement should be updated before release and the app
should make the change clear to users.
