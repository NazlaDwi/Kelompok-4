def celsius_ke_fahrenheit(celsius):
    """ Mengubah suhu celsius ke fahrenheit """
    if 
    return (celsius * 9/5) + 32

def celsius_ke_kelvin(celsius):
    """ Mengubah suhu celsius ke kelvin"""
    return ( celsius + 273.15)

celsius = float(input("Masukan suhu dalam celsius"))

fahrenheit = celsius_ke_fahrenheit(celsius)
kelvin = celsius_ke_kelvin(celsius)

print("\nHasil Konversi Suhu")
print("Celsius :", celsius, "C")
print("Fahrenheit:", fahrenheit, "F")
print("Kelvin :", kelvin, "K")


def rata_rata(nilai_list):
    valid = [n for n in nilai_list if 0 <= n <= 100]
    return sum(valid) / len(valid) if valid else 0

def laporan(nama, nilai_list):
    rata = rata_rata(nilai_list)

    print(f"Siswa : {nama}")
    print(f"Rata2 : {rata:.1f} -> {'LULUS' if rata >= 75 else 'TIDAK LULUS'}")

# Pengguna
laporan("Salwa", [80, 85, 90, 75, 100])
