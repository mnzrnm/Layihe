# Layihe

print('hello python')
metin=input('informasiya tehlukesizliyinde yeni nesil texnologiyalar')
a=[]
for m in metin:
    a.append(ord(m))
print(a)
sifre=input('vpn texnologiyasi')
a=[]
for b in sifre:
    a.append(ord(b))
ch=[]
for r in a:
    r=int(r)
    ch.append(r)
ch=(ch*(len(a)//len(ch)))+ch[:(len(a)%len(ch))]
print(ch)
print('Burada acarin ve metnin elementlerinin cemi yazlib')
y=0
F=[]
while y<len(a):
    F.append((a[y])+(ch[y]))
    y=y+1
print(F)
print('Burada cemi BIN-e cevirir ')
d=[]
for hee in F:
    d.append(bin(hee))
print(d)
print('Burada metnin sifrelenmis formasi gorsenir')
H=[]
for  yaz in F:
    H.append(chr(yaz))
print(H)
