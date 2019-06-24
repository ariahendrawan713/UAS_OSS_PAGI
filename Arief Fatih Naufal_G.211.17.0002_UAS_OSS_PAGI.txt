def Penjumlahan():
	hasil=500+200
	return hasil
  
def Penjumlahan(*kwargs):
	hasil=500+200
	return hasil
  
def Pengurangan():
	hasil=700-190
	return hasil
  
def Pengurangan(*kwargs):
	hasil=700-190
	return hasil
  
def Tampil(func,func1):
	print ("Anto memiliki bebek {} ekor di Mataram".format(func))
	print ("Bebek anto pada tahun 2013 menjadi {} karena mati keracunan".format(func1))

def Utama():
	Tampil(Penjumlahan(),Pengurangan())

#pemanggilan fungsi Utama
Utama()
