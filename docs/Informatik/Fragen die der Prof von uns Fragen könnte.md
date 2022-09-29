# Fragen die der Prof uns Fragen könnte

Bei JOptionPane, wieso schreibt man immer "null" am anfang ?
- Der erste Parameter ist dafür, dass Elemente gesperrt werden, während der Dialog erscheint. Wenn wir "null" eingeben, dann tut es das halt nicht :D
---
Wofür brauche ich das DefaultTableModel ?
- Der Hauptgrund für das benutzen des DefaultTableModel ist, dass wir die Methode "addRow()" und "removeRow()" benutzen können.
---
Wieso haben wir NetBeans genutzt und nicht IntelliJ?
- Wir haben NetBeans, auftrund seines comfortablen GUI Builders genutzt.
---
Wieso haben wir LocalDate benutzt für das Datum anstatt String ?
- Wir haben LocalDate anstatt String benutzt, damit wir die Methoden wie "isBefore" oder "isAfter" nutzen können, um überschneidungen der Aufträge der Arbeiter zu verhindern.

---
Wofür ist die Methode "stringZuDatumKonvertieren"
- Die Methode ist dafür da, dass ich ein String zu einem "LocalDate" konvertieren kann. Leider musste man das über eine externe Methode machen, weil es bei dem JOptionPane nicht sowas wie "toDateTime" gibt.
  
---
Was ist der Unterscheid zwischen "FileWriter" und "PrintWriter"
Nach dem Start der main-Methode wird ein sogenannter FileWriter er-  
zeugt, der (wie der Name vermuten lässt) das Schreiben in eine Datei erlaubt.  
Da der FileWriter nur das Schreiben einzelner Zeichen ermöglicht, und dies  
bei größeren Datenmengen etwas mühselig ist, erzeugen wir zusätzlich einen .
PrintWriter, mit dem ganze Zeilen auf einmal geschrieben werden können.

