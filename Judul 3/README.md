# 🧩 Configure VLANs & Trunking (Physical Mode)

🎥 [Tonton videonya di YouTube](https://youtu.be/7MqXjh86OMM)

---

### 💡 Deskripsi
Latihan ini ngajarin cara bikin **VLAN dan trunk** di Cisco Packet Tracer *Physical Mode*.
Tujuannya biar jaringan lebih **teratur, aman, dan nggak nyampur kayak jaringan warnet 2009**

---

### ⚙️ Langkah Singkat
1. **Bangun topologi:** 2 switch (S1, S2) dan 2 PC (PC-A, PC-B).
2. **Buat VLAN:**
   - VLAN 10 → Operations
   - VLAN 20 → Parking_Lot
   - VLAN 99 → Management
   - VLAN 1000 → Native
3. **Assign port:**
   - PC-A → VLAN 10
   - PC-B → VLAN 10
4. **Konfigurasi trunk di F0/1** supaya VLAN bisa “ngobrol” antar switch.
5. **Ubah native VLAN ke 1000** biar aman dan nggak default-default amat.

---

### ✅ Hasil Akhir
- S1 ↔ S2 → ✅ Ping sukses
- PC-A ↔ PC-B → ✅ Bisa komunikasi
- PC ke VLAN lain → ❌ Nggak bisa (belum ada router)

---