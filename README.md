# ECAI
Private Sub CommandButton1_Click()

    Worksheets(1).Range("B5").FormatConditions(1).Interior.Color = Range("D5").Interior.Color
    Worksheets(1).Range("B5").FormatConditions(2).Interior.Color = Range("D6").Interior.Color
    Worksheets(1).Range("B5").FormatConditions(3).Interior.Color = Range("D7").Interior.Color
    Worksheets(1).Range("B5").FormatConditions(4).Interior.Color = Range("D8").Interior.Color
    Worksheets(1).Range("B5").FormatConditions(5).Interior.Color = Range("D9").Interior.Color
    
    Worksheets(2).Range("B5").FormatConditions(1).Interior.Color = Range("D5").Interior.Color
    Worksheets(2).Range("B5").FormatConditions(2).Interior.Color = Range("D6").Interior.Color
    Worksheets(2).Range("B5").FormatConditions(3).Interior.Color = Range("D7").Interior.Color
    Worksheets(2).Range("B5").FormatConditions(4).Interior.Color = Range("D8").Interior.Color
    Worksheets(2).Range("B5").FormatConditions(5).Interior.Color = Range("D9").Interior.Color
    
    Worksheets(3).Range("C3").FormatConditions(1).Interior.Color = Range("D5").Interior.Color
    Worksheets(3).Range("C3").FormatConditions(2).Interior.Color = Range("D6").Interior.Color
    Worksheets(3).Range("C3").FormatConditions(3).Interior.Color = Range("D7").Interior.Color
    Worksheets(3).Range("C3").FormatConditions(4).Interior.Color = Range("D8").Interior.Color
    Worksheets(3).Range("C3").FormatConditions(5).Interior.Color = Range("D9").Interior.Color
    
    Worksheets(4).Range("D3").FormatConditions(1).Interior.Color = Range("D5").Interior.Color
    Worksheets(4).Range("D3").FormatConditions(2).Interior.Color = Range("D6").Interior.Color
    Worksheets(4).Range("D3").FormatConditions(3).Interior.Color = Range("D7").Interior.Color
    Worksheets(4).Range("D3").FormatConditions(4).Interior.Color = Range("D8").Interior.Color
    Worksheets(4).Range("D3").FormatConditions(5).Interior.Color = Range("D9").Interior.Color
    
    Worksheets(5).Range("A2").FormatConditions(1).Interior.Color = Range("D5").Interior.Color
    Worksheets(5).Range("A2").FormatConditions(2).Interior.Color = Range("D6").Interior.Color
    Worksheets(5).Range("A2").FormatConditions(3).Interior.Color = Range("D7").Interior.Color
    Worksheets(5).Range("A2").FormatConditions(4).Interior.Color = Range("D8").Interior.Color
    Worksheets(5).Range("A2").FormatConditions(5).Interior.Color = Range("D9").Interior.Color
    
    MsgBox "Colores establecidos"
    
End Sub

---
