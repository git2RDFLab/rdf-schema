# git2RDFLab-Schema

```
@prefix git: <https://purl.archive.org/purl/git2rdflab-test/git2RDFLab-git#> .
@prefix platform: <https://purl.archive.org/purl/git2rdflab-test/git2RDFLab-platform#> .
@prefix github: <https://purl.archive.org/purl/git2rdflab-test/git2RDFLab-platform-github#> .
```

| Schema | Description |
|--|--|
| `git2RDFLab-git` | Contains clases for a Git representation of a repository, including branches, commits and diffs. |
| `git2RDFLab-platform` | Contains common base-classes for multiple external service platforms (tickets/issues). |
| `git2RDFLab-platform-github` | Contains specific classes and sub-classes extending the common platform classes for the named service (like Github, Gitlab, BitBucket, Jira). |

