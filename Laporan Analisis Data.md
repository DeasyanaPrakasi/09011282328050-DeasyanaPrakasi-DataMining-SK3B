# Laporan Hasil Eksplorasi dan Analisis Data
## info Dataset

- Nama Dataset : Lefe Expectancy Data
- 
- Link : kaggle datasets download -d kumarajarshi/life-expectancy-who
### penjelasan nama data
1. Country               : Nama negara.
2. Year                  : Tahun pengambilan.
3. Status                : status ekonomi atau kesehatan negara.
4. Life expectancy       : Harapan hidup, yaitu rata-rata jumlah tahun seseorang diperkirakan dapat hidup.
5. Adult Mortality       : Jumlah kematian orang dewasa per 1.000 populasi.
6. Infant deaths         : Jumlah kematian bayi per 1.000 kelahiran hidup.
7. Alcohol               : Konsumsi alkohol per kapita dalam liter per tahun.
8. Percentage expenditure: Persentase pengeluaran negara untuk kesehatan dari total pengeluaran nasional atau GDP.
9. Hepatitis B           : Persentase anak yang divaksinasi Hepatitis B pada usia 1 tahun.
10. Measles              : Jumlah kasus campak yang dilaporkan per 1.000.000 populasi.
11. BMI (Body Mass Index): Indeks massa tubuh rata-rata dari populasi di negara tersebut.
12. Under-five deaths    : Jumlah kematian anak di bawah usia lima tahun per 1.000 kelahiran hidup.
13. Polio                : Persentase anak yang divaksinasi Polio pada usia 1 tahun.
14. Total                : Ini mungkin merujuk pada total angka atau nilai dari kolom yang relevan.
## Informasi Dataset
•	Memiliki 2938 baris dan 22 columb

•	Tipe data yang dipakai yaitu float, integer, dan object

## nilai missing dan outliers.

•	Data yang missing adalah Life expectancy (10) Adult Mortality (10) Alcohol (194)Hepatitis BMI(34) Polio(19) Total expenditure(226) Diphtheria(19) GDP(448) Population(652) thinness  1-19 years(34) thinness 5-9 years(34) Income composition of resources(167) Schooling(163)

•	Nilai yang Outliers adalah Life expectancy Adult Mortality infant deaths percentage expenditure Hepatitis B Measles under five deaths Polio Diphtheria HIV/AIDS GDP Population thinness  1-19 years thinness 5-9 years Income composition of resources Schooling dan data yang memiliki nilai outliers tertinggi adalah Measles dan GDP

## Analisis Data ( mean, median, mode, standard deviation, variance, dan quartiles)

•	Data Year

Data cenderung terkumpul di sekitar tahun 2007 dengan sedikit variasi sekitar ±4 tahun. Tahun 2013 muncul lebih sering dibandingkan tahun lainnya, yang menunjukkan bahwa data dari tahun itu lebih banyak atau lebih representatif.

•	Life Expectancy

Harapan hidup rata-rata adalah 69 tahun, sementara median sedikit lebih tinggi, menunjukkan bahwa setengah dari data berada di atas 72 tahun. Ada variasi yang cukup besar, dengan standar deviasi 9.52, yang menunjukkan perbedaan signifikan dalam harapan hidup antara berbagai entitas dalam data.

•	 Adult Mortality

Angka kematian dewasa rata-rata cukup tinggi, yaitu 164,80, sedangkan median lebih rendah pada 144, menunjukkan bahwa sebagian besar data memiliki angka kematian yang lebih rendah dari rata-rata. Mode yang sangat rendah, yaitu 12, menunjukkan adanya kasus ekstrem dengan angka kematian dewasa yang sangat rendah.

•	 Infant Deaths

Rata-rata kematian bayi adalah 30,3, tetapi median jauh lebih rendah, yaitu 3, menunjukkan bahwa sebagian besar data memiliki angka kematian yang rendah. Mode yang bernilai 0 menunjukkan bahwa dalam beberapa kasus, tidak ada kematian bayi sama sekali.

•	Alcohol

Rata-rata konsumsi alkohol adalah 4,60, tetapi median lebih rendah, menunjukkan bahwa sebagian besar data berada di bawah rata-rata. Mode yang sangat rendah, yaitu 0,01, menunjukkan bahwa ada beberapa data dengan konsumsi alkohol yang sangat kecil.

•	Percentage Expenditure

Ada perbedaan besar antara rata-rata dan median, dengan rata-rata yang jauh lebih tinggi daripada median. Mode 0 menunjukkan bahwa ada beberapa entitas yang tidak mengeluarkan anggaran sama sekali. Variasi yang sangat besar dalam pengeluaran menunjukkan adanya data ekstrem.

•	Hepatitis B

Rata-rata cakupan vaksinasi Hepatitis B adalah 80,94%, tetapi median lebih tinggi, menunjukkan bahwa sebagian besar cakupan vaksinasi sebenarnya lebih baik dari rata-rata. Mode yang sangat tinggi, yaitu 99%, menunjukkan bahwa ada beberapa data dengan cakupan vaksinasi yang sangat tinggi.

• Measles

Rata-rata kasus campak sangat tinggi, yaitu 2419, tetapi median sangat rendah pada 17, menunjukkan bahwa sebagian besar data memiliki angka kasus campak yang rendah. Mode yang bernilai 0 menunjukkan bahwa banyak kasus tidak melaporkan adanya kasus campak.

•	BMI

Rata-rata BMI adalah 38,32, dan median yang lebih tinggi menunjukkan bahwa setengah dari data memiliki BMI yang lebih tinggi dari rata-rata. Mode BMI yang sangat tinggi, yaitu 58,5, menunjukkan adanya kelompok dengan BMI ekstrem.

• Under-five Deaths

Rata-rata kematian anak di bawah lima tahun adalah 42,04, tetapi median jauh lebih rendah, yaitu 4, menunjukkan bahwa sebagian besar data memiliki angka kematian yang rendah. Mode 0 menunjukkan bahwa beberapa data tidak melaporkan kematian anak sama sekali.

• Polio
Rata-rata cakupan vaksinasi Polio adalah 82.55%, dengan median yang lebih tinggi menunjukkan cakupan yang lebih baik dalam sebagian besar data. Mode yang sangat tinggi (99%) menunjukkan cakupan vaksinasi yang sangat tinggi pada beberapa data.

• Total Expenditure

Pengeluaran total rata-rata sedikit lebih tinggi dari median, menunjukkan bahwa sebagian besar data berada di sekitar nilai rata-rata. Mode menunjukkan nilai pengeluaran yang sering muncul.

• Diphtheria

Rata-rata cakupan vaksinasi Difteri adalah 82.32%, dengan median yang lebih tinggi menunjukkan cakupan yang lebih baik dalam sebagian besar data. Mode yang sangat tinggi (99%) menunjukkan cakupan vaksinasi yang sangat tinggi dalam beberapa data.

• HIV/AIDS

Rata-rata prevalensi HIV/AIDS adalah 1.74%, tetapi median yang jauh lebih rendah menunjukkan prevalensi yang rendah pada sebagian besar data. Mode 0.1% menunjukkan prevalensi yang sangat rendah di banyak entitas.

•  GDP

Rata-rata GDP sangat tinggi dibandingkan median, menunjukkan adanya data dengan GDP yang sangat tinggi. Variasi yang besar menunjukkan perbedaan yang signifikan dalam kekayaan ekonomi antar entitas.

•  GDP

Rata-rata populasi sangat tinggi dibandingkan median, menunjukkan bahwa sebagian besar data memiliki populasi yang jauh lebih kecil dari rata-rata. Variasi yang sangat besar menunjukkan adanya data dengan populasi yang sangat besar.

• Thinness 1-19 years

Rata-rata kekurangan berat badan pada usia 1-19 tahun adalah 4.84, dengan median yang lebih rendah menunjukkan prevalensi yang lebih umum pada nilai yang lebih rendah. Mode 1 menunjukkan kekurangan berat badan yang sangat rendah dalam beberapa kasus.

• Thinness 5-9 years

Rata-rata kekurangan berat badan pada usia 5-9 tahun adalah 4.87, dengan median yang lebih rendah menunjukkan 
bahwa banyak data memiliki angka kekurangan berat badan yang rendah. Mode 0.9 menunjukkan prevalensi yang sangat rendah.

• Income Composition of Resources

Rata-rata komposisi pendapatan adalah 0.63 dengan median sedikit lebih tinggi, menunjukkan bahwa sebagian besar data memiliki nilai komposisi pendapatan yang sedikit lebih baik dari rata-rata. Mode 0 menunjukkan ada entitas dengan distribusi pendapatan yang sangat rendah.

• Schooling

Rata-rata tahun pendidikan adalah 11.99 tahun dengan median yang sedikit lebih tinggi, menunjukkan bahwa banyak data memiliki pendidikan di atas rata-rata. Mode menunjukkan nilai pendidikan yang umum dalam data. Variasi yang relatif kecil menunjukkan homogenitas yang lebih besar dalam tingkat pendidikan.

### Korelasi Positif Tinggi
**1. Life expectancy dengan Schooling (0.75)**
   - Ini menunjukkan bahwa semakin tinggi tingkat Schooling di suatu negara, semakin tinggi pula harapan hidup (Life expectancy). Pendidikan yang lebih baik biasanya berkorelasi dengan pengetahuan kesehatan yang lebih baik dan akses yang lebih baik ke layanan kesehatan.

**2. Life expectancy dengan Income composition of resources (0.72)**
   - Korelasi ini menunjukkan bahwa semakin tinggi kIncome composition of resources, semakin tinggi harapan hidup. Ini bisa berarti bahwa negara dengan sumber daya ekonomi yang lebih baik cenderung memiliki populasi yang lebih sehat dan umur yang lebih panjang.

**3. Schooling dengan Income composition of resources (0.80)**
   - Ini menunjukkan hubungan erat antara pendidikan dan komposisi pendapatan. Negara yang memiliki pendapatan sumber daya yang lebih tinggi cenderung juga memiliki sistem pendidikan yang lebih baik.

**4. Thinness 1-19 years dengan Thinness 5-9 years (0.94)**
   - Korelasi ini sangat kuat dan menunjukkan bahwa tingkat thinness pada anak-anak usia 1-19 tahun sangat berkaitan dengan tingkat kekurusan pada anak-anak usia 5-9 tahun.

**5. BMI dengan Life expectancy (0.57)**
   - Korelasi positif ini menunjukkan bahwa BMI yang lebih tinggi terkait dengan harapan hidup yang lebih tinggi. Namun, ini tidak berarti BMI yang lebih tinggi selalu baik, karena tergantung pada konteks kesehatan lainnya.

### Korelasi Negatif Tinggi
**1. Life expectancy dengan Adult Mortality (-0.70)**
   - Korelasi negatif ini menunjukkan bahwa semakin tinggi angka kAdult Mortality, semakin rendah harapan hidup. Ini masuk akal karena kematian dewasa yang tinggi biasanya menurunkan rata-rata usia harapan hidup.

**2. Life expectancy dengan HIV/AIDS (-0.56)**
   - Tingginya prevalensi HIV/AIDS berkorelasi dengan harapan hidup yang lebih rendah, yang menunjukkan dampak buruk dari epidemi ini terhadap kesehatan masyarakat dan umur panjang.

**3. Adult Mortality dengan Schooling (-0.45)**
   - Korelasi ini menunjukkan bahwa tingkat pendidikan yang lebih tinggi berkaitan dengan tingkat kematian dewasa yang lebih rendah. Pendidikan dapat mempengaruhi kesadaran kesehatan, yang pada gilirannya mengurangi angka kematian.

**4. Thinness 1-19 years dengan Life expectancy (-0.48)**
   - Ini menunjukkan bahwa tingkat kekurusan pada anak-anak dan remaja berkorelasi negatif dengan harapan hidup. Kekurusan yang parah seringkali menunjukkan malnutrisi, yang bisa berdampak buruk pada umur panjang.

**5. Thinness 5-9 years dengan Life expectancy (-0.47)**
   - Sama seperti di atas, ini menunjukkan bahwa kekurusan pada usia dini berkaitan dengan harapan hidup yang lebih rendah.



