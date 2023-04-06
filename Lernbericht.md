# Lern-Bericht
Carnation Eisenring, Bashiri, Martullo
## Einleitung

Wir haben mit Unity ein Rennspiel erstellt.

## Was habe ich gelernt?

Wir haben gelernt, wie man einen Code schreibt, welches einem Auto ermöglicht, zu lenken.
## Beschreibung

In unserem Skript wird das Lenken des Autos durch die Funktion "HandleSteering()" gesteuert. Die aktuelle Lenkrichtung wird dabei auf Basis
der Spieler-Eingabe berechnet und auf die Vorderräder des Fahrzeugs übertragen.

Zunächst wird der Lenkwinkel berechnet, indem der maximale Lenkwinkel des Autos mit der horizontalen Eingabe des Spielers multipliziert wird. Wenn der Spieler das Lenkrad nach links dreht, wird eine negative horizontale Eingabe erzeugt, die einen negativen Lenkwinkel ergibt und das Auto nach links lenkt. Dreht der Spieler das Lenkrad nach rechts, wird eine positive horizontale Eingabe erzeugt, die einen positiven Lenkwinkel ergibt und das Auto nach rechts lenkt.

Sobald der Lenkwinkel berechnet ist, wird er auf die Vorderräder des Autos angewendet, indem er auf die "steerAngle"-Eigenschaft der entsprechenden WheelCollider-Komponenten gesetzt wird. Dadurch wird der Winkel der Vorderräder geändert und das Fahrzeug lenkt in die gewünschte Richtung.

```csharp
private void HandleSteering()
{
currentSteerAngle = maxSteerAngle * horizontalInput;
frontLeftWheelCollider.steerAngle = currentSteerAngle;
frontRightWheelCollider.steerAngle = currentSteerAngle;
}
```



https://user-images.githubusercontent.com/111045891/230327861-2be91c84-71c9-4ed8-82a4-f45db81104f7.mp4



## Verifikation
Text: Wie das Lenken funktioniert.

Code: Ausschnitt aus unserem Projekt, welches das Lenken regelt.

Video: Wie es schlussendlich in unserem Projekt aussieht.

# Reflexion zum Arbeitsprozess

Was gut lief:

Die Kommunikation in unserem Team lieft gut, da man immer wusste, an was der andere am Arbeiten ist. Man konnte sich dann auch gerade helfen.

Was nicht gut lief:

Wir haben oft nicht effizient genug gearbeitet, was auch Grund dafür war, dass wir nicht alle unsere Ziele erreichten.

**VBV**: 

Beim nächsten Mal probieren wir uns gegenseitig mehr zu motivieren, damit wir schneller in unserem Projekt vorankommen.
