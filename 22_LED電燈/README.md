# LED電燈

- 問題：不會亮

- case 1：
  
  利用三用電錶量測每顆LED是否會亮，並將不會亮的移除掉，再短路即可。

- case 2：
  
  老師，像這種情形，大概一半不會亮，一半要亮不亮，會閃爍，輸出電壓正常，大概DC100v，用電錶量每顆LED都不會亮，是代表每顆LED都壞了？

- 老師回覆：
  - LED燈泡的結構！有1:從頭串到尾的2:雙串/並聯3:有多串/並聯，無法隔空猜測，唯一還是要用電表量測，但LED燈蕊有單一3v,有2顆/1燈蕊（6v），有複顆/1燈蕊（9v，12v），所以不是一以貫之，那麼單純，三用電表的內部電池也只有1.5v or 3v,無法量測多蕊的LED! 基本功/經驗/學理，要融會貫通，三個月一學期，只是興趣的開始，後續還有的機會學習！
  - 仔細看LED板面！有3x6的字樣，total LED的數量是18顆，3x6=18，所以合理猜測此LED是6串/三並，以上是隔空推測，還需用電表驗證！
  - 6個特別亮的可能是同一組的，請用電表量測其中一顆的電壓？是多少，即可知此燈蕊內部是多少顆組成的！完全不亮那組可能有一顆不良！
  - LED在閃爍，應是驅動板有問題！
