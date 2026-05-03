<!-- mtoc-start -->

* [branch model](#branch-model)
* [commit message](#commit-message)

<!-- mtoc-end -->
# branch model

- GitHub Flowを採用する
- ブランチを作成する場合は、<type>/<issue-number>-<short-description>`の形式にする

| type | 意味 | 例 |
|---|---|---|
| `feature` | 新機能追加 | `feature/12-add-asset-summary` |
| `fix` | バグ修正 | `fix/13-correct-tax-calculation` |
| `docs` | ドキュメント修正 | `docs/14-update-readme` |
| `refactor` | 振る舞いを変えないコード整理 | `refactor/15-split-tax-service` |
| `test` | テスト追加・修正 | `test/16-add-tax-service-test` |
| `chore` | 設定変更・依存関係更新などの雑務 | `chore/17-setup-github-actions` |


# commit message

- コミットメッセージは Conventional Commits を参考にする
- コミットメッセージは、`<type>: <short-description>` の形式にする

| type | 意味 | 例 |
|---|---|---|
| `feat` | 新機能追加 | `feat: add asset summary` |
| `fix` | バグ修正 | `fix: correct tax calculation` |
| `docs` | ドキュメント修正 | `docs: update README` |
| `refactor` | 振る舞いを変えないコード整理 | `refactor: split tax service` |
| `test` | テスト追加・修正 | `test: add tax service tests` |
| `chore` | 設定変更・依存関係更新などの雑務 | `chore: update dependencies` |
| `style` | コードの意味に影響しない整形 | `style: format user controller` |
| `ci` | CI設定の変更 | `ci: add GitHub Actions workflow` |
| `build` | ビルド設定・依存関係の変更 | `build: update Maven config` |
| `perf` | パフォーマンス改善 | `perf: optimize asset query` |

