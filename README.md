// C++ code<br>

void setup()<br>
{<br>
  pinMode(10, OUTPUT); <br>
  pinMode(9, OUTPUT); <br>
  pinMode(8, OUTPUT); <br>
  pinMode(7, OUTPUT); <br>
  pinMode(6, OUTPUT); <br>
  pinMode(5, OUTPUT); <br>
}

void loop()<br>
{<br>
  digitalWrite(10,HIGH);<br>
  digitalWrite(9, LOW); <br>
  digitalWrite(8, LOW);<br>
  digitalWrite(7, LOW);<br>
  digitalWrite(6, LOW);<br>
  digitalWrite(5, HIGH);<br>
  delay(5000); // Wait for 1000 millisecond(s)<br>
  digitalWrite(10,HIGH);<br>
  digitalWrite(9, LOW);<br>
  digitalWrite(8, LOW);<br>
  digitalWrite(7, LOW);<br>
  digitalWrite(6, HIGH);<br>
  digitalWrite(5, LOW);<br>
  delay(5000); // Wait for 1000 millisecond(s)<br>
  digitalWrite(10,LOW);<br>
  digitalWrite(9, LOW);<br>
  digitalWrite(8, HIGH);<br>
  digitalWrite(7, HIGH);<br>
  digitalWrite(6, LOW);<br>
  digitalWrite(5, LOW);<br>
  delay(5000); // Wait for 1000 millisecond(s)<br>
  digitalWrite(10,LOW);<br>
  digitalWrite(9, HIGH); <br>
  digitalWrite(8, LOW);<br>
  digitalWrite(7, HIGH);<br>
  digitalWrite(6, LOW);  <br>
  digitalWrite(5, LOW);<br>
  delay(5000); // Wait for 1000 millisecond(s)<br>
}
 
