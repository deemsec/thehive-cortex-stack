# Gunakan image Cortex resmi sebagai dasar
FROM thehiveproject/cortex:latest

# Pindah ke user root untuk memiliki izin instalasi
USER root

# Jalankan perintah instalasi pip
RUN pip install cortexutils

# Kembali ke user cortex default untuk menjalankan aplikasi
USER cortex
