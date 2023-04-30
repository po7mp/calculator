from PyQt5.QtWidgets import*
app = QApplication([])
okno = QWidget()
textchisla=""
line1 = QVBoxLayout()
okno.setLayout(line1)
line2 = QHBoxLayout()
line1.addLayout(line2)
text1 = QLabel("+")
line1.addWidget(text1)
vvod1= QLineEdit()
line1.addWidget(vvod1)
chislo1 = vvod1.text()
vvod2= QLineEdit()
line2.addWidget(vvod2)
chislo2 = vvod2.text()
text2 = QLabel("=")
line1.addWidget(text2)
text3 = QPushButton('Найти')
line1.addWidget(text3)

def plus():
    a = int(vvod1.text())
    b = int(vvod2.text())
    text2.setText(str(a+b))

text3.clicked.connect(plus)

text1.setStyleSheet('''
QLabel{color:green; 
font-size: 25px;
}
''')


text2.setStyleSheet('''
QLabel{color:green;
font-size: 25px;
} 
''')


text3.setStyleSheet('''
QPushButton{color:green;
font-size: 25px;
background:pink;
} 
''')

okno.setStyleSheet('''
QWidget{
background:qlineargradient(
x0: 0,y0:0,x1: 2,y1:3
stop: 0 green, stop: 1 pink    
);   
}
''')



okno.show()
app.exec_()
