import qrcode
data = "QR IS HERE"

qr = qrcode.make(data)
qr.save("myqrcode.png")

print("Scucessfully generate1")
