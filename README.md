```html
<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Proses Transkripsi Sumber Lisan</title>

<style>
:root {
    --ink: #51435e;
    --pink: #ffe5ee;
    --lilac: #e8ddff;
    --blue: #dff5ff;
    --mint: #dcf8e8;
    --purple: #9274c7;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    color: var(--ink);
    font-family: "Trebuchet MS", Arial, sans-serif;
    line-height: 1.75;
    background-color: #fff9fc;
    background-image: radial-gradient(
        #ffd7e5 1.4px,
        transparent 1.4px
    );
    background-size: 22px 22px;
}

header {
    text-align: center;
    padding: 35px 20px;
    background: linear-gradient(
        135deg,
        #ffe3ee,
        #eee4ff 55%,
        #e0f6ff
    );
    border: 4px solid white;
    border-radius: 0 0 36px 36px;
    box-shadow: 0 7px 0 #f5c9dc;
}

.label {
    display: inline-block;
    background: #fffdfb;
    border: 2px solid #f8c1d5;
    border-radius: 99px;
    padding: 5px 15px;
    font-size: 0.84rem;
    font-weight: 900;
}

h1 {
    font-size: clamp(2rem, 5vw, 3.5rem);
    line-height: 1.2;
    margin: 14px 0 0;
    color: #7656a5;
}

h1 span {
    color: #ed78a4;
}

main {
    max-width: 1000px;
    margin: 0 auto;
    padding: 28px 18px 50px;
}

.intro {
    margin: 0 0 25px;
    background: white;
    border: 3px dashed #f5bfd3;
    border-radius: 24px;
    padding: 20px 23px;
    box-shadow: 0 5px 0 #f9e0e9;
}

.intro p {
    margin: 0;
}

.grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px;
}

.card {
    padding: 22px;
    border: 3px solid white;
    border-radius: 26px;
    box-shadow: 0 6px 0 #ead8e6;
    transition: transform 0.2s ease;
}

.card:hover {
    transform: translateY(-4px);
}

.card:nth-child(7n+1) {
    background: var(--pink);
}

.card:nth-child(7n+2) {
    background: var(--lilac);
}

.card:nth-child(7n+3) {
    background: var(--mint);
}

.card:nth-child(7n+4) {
    background: var(--blue);
}

.card:nth-child(7n+5) {
    background: #fff0d9;
}

.card:nth-child(7n+6) {
    background: #fce6f7;
}

.card:nth-child(7n) {
    background: #e5f7ee;
}

.card h2 {
    display: flex;
    align-items: flex-start;
    gap: 11px;
    font-size: 1.15rem;
    line-height: 1.4;
    margin: 0 0 12px;
    color: #654e83;
}

.num {
    width: 40px;
    height: 40px;
    flex: 0 0 40px;
    display: grid;
    place-items: center;
    border-radius: 50%;
    background: white;
    border: 2px solid #f5c5d9;
    color: #8c68b6;
    font-size: 1.15rem;
    font-weight: 900;
    box-shadow: 0 3px 0 #e4c7dc;
}

.flower {
    font-size: 1.15rem;
    margin-right: 5px;
}

.card p {
    margin: 0;
    font-size: 1rem;
}

/* Paparan telefon dan tablet */
@media (max-width: 650px) {
    .grid {
        grid-template-columns: 1fr;
    }

    .card {
        padding: 19px;
    }

    header {
        padding: 25px 15px;
    }
}

/* Kurangkan animasi jika diperlukan */
@media (prefers-reduced-motion: reduce) {
    .card {
        transition: none;
    }
}
</style>
</head>

<body>

<header>
    <div class="label">🌷 Sejarah Lisan 🌷</div>

    <h1>
        Proses <span>Transkripsi</span><br>
        Sumber Lisan
    </h1>
</header>

<main>

    <section class="intro">
        <p>
            Transkripsi sumber lisan ialah proses menukarkan rakaman
            temu bual yang berbentuk audio atau video kepada teks
            bertulis. Proses ini penting dalam kajian sejarah lisan
            kerana maklumat yang disampaikan oleh informan dapat
            direkodkan, disusun dan dianalisis dengan lebih mudah.
            Terdapat beberapa langkah yang boleh dilakukan dalam
            proses transkripsi sumber lisan.
        </p>
    </section>

    <section class="grid">

        <!-- LANGKAH 1 -->
        <article class="card">
            <h2>
                <span class="num">1</span>
                <span>
                    <span class="flower">🎧</span>
                    Mendengar Rakaman Temu Bual
                </span>
            </h2>

            <p>
                Penyelidik perlu mendengar rakaman temu bual secara
                keseluruhan untuk memahami isi perbualan dan mengenal
                pasti maklumat penting yang disampaikan oleh informan.
                Rakaman boleh dimainkan berulang kali bagi memastikan
                maklumat yang diperoleh jelas dan tepat.
            </p>
        </article>

        <!-- LANGKAH 2 -->
        <article class="card">
            <h2>
                <span class="num">2</span>
                <span>
                    <span class="flower">✍️</span>
                    Menukarkan Rakaman kepada Teks
                </span>
            </h2>

            <p>
                Penyelidik menulis semula perkataan dan ayat yang
                dituturkan oleh informan berdasarkan rakaman temu bual.
                Proses ini perlu dilakukan dengan teliti supaya
                maklumat yang dicatatkan tidak mengubah maksud asal
                yang disampaikan oleh informan.
            </p>
        </article>

        <!-- LANGKAH 3 -->
        <article class="card">
            <h2>
                <span class="num">3</span>
                <span>
                    <span class="flower">🔎</span>
                    Menandakan Maklumat yang Tidak Jelas
                </span>
            </h2>

            <p>
                Sekiranya terdapat perkataan atau ayat yang kurang
                jelas dalam rakaman, penyelidik perlu mendengar semula
                bahagian tersebut. Jika maklumat masih tidak dapat
                dikenal pasti, penyelidik boleh menandakan bahagian itu
                sebagai <em>[tidak jelas]</em> dan bukannya membuat
                andaian sendiri.
            </p>
        </article>

        <!-- LANGKAH 4 -->
        <article class="card">
            <h2>
                <span class="num">4</span>
                <span>
                    <span class="flower">✅</span>
                    Menyemak Ketepatan Transkripsi
                </span>
            </h2>

            <p>
                Selepas transkripsi selesai, penyelidik perlu
                membandingkan teks bertulis dengan rakaman asal.
                Langkah ini bertujuan memastikan tiada maklumat penting
                yang tertinggal, tersalah catat atau diubah sehingga
                menjejaskan maksud sebenar informan.
            </p>
        </article>

        <!-- LANGKAH 5 -->
        <article class="card">
            <h2>
                <span class="num">5</span>
                <span>
                    <span class="flower">📝</span>
                    Menyunting dan Menyusun Teks
                </span>
            </h2>

            <p>
                Penyelidik boleh membetulkan kesalahan ejaan, tanda
                baca dan susunan perenggan supaya teks lebih mudah
                dibaca. Walau bagaimanapun, penyuntingan tidak boleh
                mengubah maksud asal atau menghilangkan ciri penting
                dalam penyampaian informan. Jika kajian memerlukan
                transkripsi secara verbatim, perkataan yang dituturkan
                perlu dikekalkan, termasuk pengulangan dan jeda yang
                relevan.
            </p>
        </article>

        <!-- LANGKAH 6 -->
        <article class="card">
            <h2>
                <span class="num">6</span>
                <span>
                    <span class="flower">🧠</span>
                    Mengenal Pasti Maklumat Penting
                </span>
            </h2>

            <p>
                Penyelidik meneliti transkripsi untuk mengenal pasti
                fakta, pengalaman, tarikh, tempat, nama individu dan
                peristiwa sejarah yang berkaitan dengan kajian.
                Maklumat tersebut boleh dikelompokkan mengikut tema
                bagi memudahkan proses analisis sejarah lisan.
            </p>
        </article>

        <!-- LANGKAH 7 -->
        <article class="card">
            <h2>
                <span class="num">7</span>
                <span>
                    <span class="flower">🗂️</span>
                    Menyimpan dan Mendokumentasikan Transkripsi
                </span>
            </h2>

            <p>
                Transkripsi yang telah disemak perlu disimpan dengan
                teratur bersama rakaman asal. Maklumat seperti nama
                atau kod informan, tarikh temu bual, lokasi temu bual
                dan nama penyelidik juga perlu direkodkan. Persetujuan
                informan serta kerahsiaan maklumat peribadi hendaklah
                dijaga.
            </p>
        </article>

    </section>

</main>

</body>
</html>
```
