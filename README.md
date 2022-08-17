# nonsense_gen

由徐子修 Bill Hsu 寫的唬爛產生器為基礎，去除裡面重複的語句，加上靜思語，修改成 AutoHotkey 的腳本。

使用時，按 Ctrl-9 就會自動送出 1000 個句子。

修改方式，在 LINE.ahk 中：
尋找 ^9::           即為觸發的 Hotkey，可自行修改。
尋找 count := 1000  這是觸發後一次送出的量。
尋找 topic :=       後面的字串就是主題。

唬爛產生器 https://howtobullshit.me/ <br>
唬爛產生器的源碼 https://github.com/StillFantastic/bullshit
