# git-set-folder-times
git-set-file-timesのフォルダ対応版

オリジナルは https://git.wiki.kernel.org/index.php/ExampleScripts#Setting_the_timestamps_of_the_files_to_the_commit_timestamp_of_the_commit_which_last_touched_them にある。

これだと、ファイルだけしか日時を変えてくれないので、見知らぬプロジェクトで最近更新があったフォルダなどが探しにくい。

そこで、フォルダ内にあるファイルのうち一番日付が新しいものの日付をフォルダの日付とするスクリプト。
