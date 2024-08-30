# try-using-github-action
測試如何使用 github action (Fast Forward Merge)

1. 看 `GitHubAction快速合併.url` 中的 github action 使用說明
2. 看 `Fast Forward Merge · Actions · GitHub Marketplace.url` 的 github action 功能說明
3. 手動生成需要的 `fast-forward-merge.yml`、`pull_request.yml` 並將檔案加到 `/.github/workflows` 目錄下
4. pull request 的目的分支, 需要有以上兩個 yml 檔, 才可以在 comment 上自動觸發 `/fast-forword` 指令
5. 可以看這個 repositories 中的 pull requests #2 項目, 即可看到 github action 的觸發流程及 comment 內容
