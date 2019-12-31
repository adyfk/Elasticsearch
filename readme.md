# sama kana semua nama cluster
# _cat/nodes untuk melihat nodes active dan siapa yang menjadi master
# minimal active setengah dari master yang menjadi inisal baru mau tercover/berjalan
# jika hanya berjalan hanya 1 nodes sebagai master , hapus data folder pada elasticsearch



# di jvm ========================
# Xms represents the initial size of total heap space
# Xmx represents the maximum size of total heap space

# -Xms1g
# -Xmx1g


# di .yml
# Make sure that the heap size is set to about half the memory available
# on the system and that the owner of the process is allowed to use this
# limit.
# Elasticsearch performs poorly when the system is swapping the memory. !!!!!!!!!!!!!!!!!!!