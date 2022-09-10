# static-marks-action

A GitHub Action wrapper for the [static-marks](https://github.com/darekkay/static-marks) project. For those unfamiliar with it, [static-marks](https://github.com/darekkay/static-marks) turns a YAML formatted collection of bookmarks into an HTML file that a browser can access statically. This project's GitHub Action supports using [static-marks](https://github.com/darekkay/static-marks) in CI/CD workflows on GitHub.

## Configuration Options

| Configuration | Description | Required? | Default value |
| --- | --- | --- | --- |
| github_token | The `GITHUB_TOKEN` or a Personal Access Token | yes | _[None]_ |
| bookmarks_file | A source YAML file | no | bookmarks.yml |
| html_file | The output HTML file | no | bookmarks.html |
| commit_message | The commit message | no | 'Update HTML bookmarks file' |
| commit_user | The user associated with the commit | no | 'github-actions[bot]' |
| commit_email | The email associated with the commit | no | '41898282+github-actions[bot]@users.noreply.github.com' |

## License

Since this is just a wrapper around static-marks, it uses the same license that static-marks uses: [The MIT License](LICENSE).

## Contact

This is just a fledgling project, but feel free to [open an issue](https://github.com/ksclarke/static-marks-action/issues) or [start a new discussion]() with bug fixes, suggestions, or questions.
