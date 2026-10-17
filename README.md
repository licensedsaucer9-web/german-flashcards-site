# LS9 Flashcards — retired compatibility site

Use the current app: <https://licensedsaucer9-web.github.io/ls9-flashcards-site/>.

The former `german-flashcards-site` Pages URL was retired on 2026-10-17.
Pages hosting is disabled and this repository is archived, retaining its Git
history and historical assets. The old URL no longer provides a supported
redirect or recovery route. Archiving alone does not disable Pages; both
operations form this retirement.

## Retirement decision

The owner explicitly requested retirement in
[issue #1](https://github.com/licensedsaucer9-web/german-flashcards-site/issues/1),
confirming that the two known users do not need the old-URL forwarding service.
This owner decision replaces further device-by-device retirement qualification;
no inspection of either user's devices or verification of unsynced local records
is claimed. Studied-data import and legacy device recovery were already waived
for the 2026-10-07 Firebase release.

Before retirement, `index.html` redirected to the current app and `sw.js` was a
retirement worker that cleared old caches, navigated open clients to the current
app, and unregistered itself. Historical assets and test-preview directories
were still present, but were not a supported current app. The active source
workflow publishes exclusively to `ls9-flashcards-site`; it has no deployment
dependency on this repository. Historical recovery-bridge commands still target
the old path and are retained as runbooks, not active hosting dependencies.

Retirement does not delete the current app, Firebase accounts or Firestore data,
the archived legacy data repository, or browser storage. Cached offline copies
on old devices may continue running; disabling hosting does not remotely erase
or update those installations. Create bookmarks and Home Screen icons from the
current app URL.

## History and recovery

The pre-retirement revision is
`6bfcdecc8dbf506ac22e155adc5c855ea170b670` on `gh-pages`. Restore hosting only as a
separate authorized operation: unarchive the repository if necessary, review
the intended artifact, then re-enable Pages from `gh-pages` at `/`. Historical
client assets must not replace the current Firebase app or its data.

Current operation and retirement records live in the
[source repository](https://github.com/licensedsaucer9-web/ls9-flashcards/blob/master/docs/rename.md).
