# package-requests

Request new content/app package for Kiwix Hotspot by [opening a ticket](https://github.com/offspot/package-requests/issues/new/choose), selecting appropriate type.

## ZIM file

All ZIM files are natively supported. ZIM files are offline, *read-only* copies of websites that can be accessed within the Hotspot.

If you want to turn a *non-interactive** website into a ZIM file, [request-it at openZIM](https://github.com/openzim/zim-requests).

## Nautilus ZIM

[nautilus](https://github.com/openzim/nautilus) creates regular ZIM files from a collection of files (and their metadata). Those can be listed and downloaded in addition to be played directly (PDF, audio and video files).

ZIM files are included in the Kiwix Library and thus largerly available to all.

Example: [Bayard](https://www.bayard-editions.com/) provides thematic books (EPUB, PDF) and Videos as Nautilus [ZIM files](http://library.kiwix.org/?lang=&q=bayard).

## Files package

Files packages are ZIP archives containing a list of files to be offered for download. Those can offer a support web page that describe the files and provide links. If not, a standard file listing is provided.

Files can be anything from content to softwares (specify target platforms in this case).

Example: [Nomad Education](https://nomadeducation.fr/) offers an Android application (`.apk`) for mobile users to download and install on their device.

## Application

Some websites cannot be turned into ZIM files, usually because they use server-side processing: ZIM files are read-only.

In this case, the application must be packaged and ran on the Hotspot.

Example: [WikiFundi](https://www.wikifundi.org/) created a wiki-editing training platform based on [Mediawiki](https://www.mediawiki.org/).


## Acceptance policy

We are yet to define an acceptance policy. In the mean time, main criterias are **impact** and **readyness**. The lesser the worke required to integrate, the higher the chances are to be included.


## Catalog

Unfortunately, we **only** have a [ZIM catalog](http://library.kiwix.org/) at the moment.