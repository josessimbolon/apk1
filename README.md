function bukaWhatsApp(nomor, pesan = "") {
    const url = `https://wa.me/${nomor}?text=${encodeURIComponent(pesan)}`;
    window.location.href = url;
}

// Contoh
bukaWhatsApp("6281234567890", "Halo");
