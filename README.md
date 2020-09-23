<div align="center">

## Blinking Title Bar


</div>

### Description

Want Attention? Let the title bar of your program blink!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[oXidizer](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/oxidizer.md)
**Level**          |Unknown
**User Rating**    |5.0 (20 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/oxidizer-blinking-title-bar__1-1522/archive/master.zip)





### Source Code

```
'***Add a timer (timer1) to your form... paste the code below to the global declarations!
'***Set the timer interval to 250
Private Declare Function FlashWindow Lib "user32" (ByVal hwnd As Long, ByVal bInvert As Long) As Long
Private Sub Timer1_Timer()
  Call FlashWindow(Form1.hwnd, True)
End Sub
```

