Lefre: Language-purpose Editing Framework of Reference Book
Lefre Specs 　.lefrespec
Lefre Articles 　.lefra
Lefre Compositions 　.lefrec

Lefre HEBA

```dart
class LefreProcessor{
  LefreProcessor();
  String heba(String lefra);
}
final LefreProcessor l = LefreProcessor();
```

sample.lefrespec

```
Title: Reference Book Title
Author: Author Name, Author Name, Author Name
Editor: Editor Name, Editor Name
Licencer: Licencer Name
License: LicenseName
LicenseDate: 2023
LicenseDateAutoUpdate: true
ReversedC: false
Repository: https://url.example.org
Init: /path/to/file.lefrec
TopSelectors:
AllAddSerectors
Avoid

```

sample.lefrec

```
{ArticleID}　節名
節本文(拡張Markdown)

{ArticleID}　節名
節本文(拡張Markdown)
```

sample.lefrec

```
!include /path/to/file.lefrec
!use /path/to/file.lefra
.chapter
.abolish
.draft
.ignore
```
