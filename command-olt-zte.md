# Melihat ONU yang belum diregister
```bash
show gpon onu uncfg
```

# Melihat ONT yang Running pada Port OLT
```bash
show run interface gpon-olt_x/y/z
```

# Melihat ONU yang Running pada Port OLT
```bash
show gpon onu state gpon-olt_x/y/z
```

# Cek Detail Config di Interface ke arah ONT
```bash
show run interface gpon-onu_x/y/z:a
```

# Melihat redaman FO
```bash
show pon power attenuation gpon-onu_x/y/z:a
```

# Melihat Traffic
```bash
show interface gpon-onu_x/y/z:a
```

Melihat Detail Info pada ONT
```bash
show gpon onu detail-info gpon-onu_x/y/z:a
```

Melihat Mac Address yang Konek ke ONT
```bash
show mac gpon onu gpon-onu_x/y/z:a
```

# Cek Status Port ONT
```bash
show gpon remote-onu interface eth gpon-onu_x/y/z:a
```

# Melihat Register ONT berdasarkan SN
```bash
show gpon onu by sn ZTEGCxxxxxx = untuk melihat ONT di Gpon-onu berapa
```

# Configurasi Ganti ONT
```bash
config
interface gpon-onu_x/y/z:a
registration-method sn ZTEGBxxxxx
```
