<thead class="sticky-thead">
    <tr>
        <th class="text-center">No</th>
        <th>Kode Iden</th>
        <th>Nama Kel</th>
        <th>Alamat Pr</th>
        <th>NIB</th>
        <th>Skala Usaha</th>
        <th>Status</th>
        <th class="text-center">Selesai</th>
    </tr>
</thead># monitoring-rt15
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Pencacahan RT 015 RW 002</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f4f6f9; padding: 20px; font-family: system-ui, -apple-system, sans-serif; }
        .card-header-custom { background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); color: white; border-radius: 15px 15px 0 0; }
        .card { border: none; border-radius: 15px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); }
        .table-responsive { max-height: 70vh; overflow-y: auto; }
        .checked-row { background-color: #d1e7dd !important; text-decoration: line-through; color: #0f5132; opacity: 0.75; }
        .sticky-thead th { position: sticky; top: 0; background-color: #212529; color: white; z-index: 10; }
        .search-box { border-radius: 20px; padding-left: 20px; }
    </style>
</head>
<body>
<div class="container-fluid max-width-lg">
    <div class="card mb-4">
        <div class="card-header-custom p-4 text-center">
            <h2 class="fw-bold mb-1">📊 Portal Monitoring Pencacahan Lapangan</h2>
            <p class="mb-0 opacity-75">Provinsi: [63] KALIMANTAN SELATAN | Kota: [71] BANJARMASIN | Kecamatan: [010] BANJARMASIN SELATAN</p>
            <span class="badge bg-warning text-dark mt-2 fw-semibold">Wilayah Tugas: [006] PEMURUS DALAM — SLS: [0015] RT 015 RW 002</span>
        </div>
        <div class="card-body bg-white p-3">
            <input type="text" id="searchInput" class="form-control search-box" placeholder="🔍 Cari nama warga, nama usaha, atau alamat di lapangan...">
        </div>
    </div>

    <div class="card bg-white p-3">
        <div class="table-responsive">
            <table class="table table-hover table-bordered align-middle" id="wargaTable">
                <thead class="sticky-thead">
                    <tr>
                        <th width="5%" class="text-center">No</th>
                        <th width="50%">Nama Keluarga / Bangunan / Usaha</th>
                        <th width="35%">Alamat Prelist</th>
                        <th width="10%" class="text-center">Selesai</th>
                    </tr>
                </thead>
                <tbody id="tableBody">
                    <tr><td class="text-center">1</td><td><strong>JL SINTUK III NO 7</strong></td><td>13 /</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">2</td><td><strong>ROSSAHIDINT ABDI / HAMIDAH</strong></td><td>JL. SINTUK III NO.4 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">3</td><td><strong>JUPRI SUPARJO / MUTIAH</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">4</td><td><strong>YULFARIZI, SE /</strong></td><td>JL. UTAN KAYU NO.49 KOMP. BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">5</td><td><strong>ACHMAD ROSADI FACHRI / FIRDA NURHALISYA</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">6</td><td><strong>SIDIK PRABOWO / WORO TALUKI</strong></td><td>JL AMPEA KOMP.BALI ASRI 1 NO B</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">7</td><td><strong>RUMAH KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">8</td><td><strong>RUMAH KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">9</td><td><strong>JULIA TJINTAWATI / TEOFILUS WENDY</strong></td><td>JL. SINTUK III NO.1</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">10</td><td><strong>RUMAH KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">11</td><td><strong>-</strong></td><td>21 /</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">12</td><td><strong>RUMAH KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">13</td><td><strong>RUMAH KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">14</td><td><strong>M. HUMAIDI RAHMI / ROSIDAH</strong></td><td>JL. SINTUK III NO.28 KOMP.BANJAR INDAH PERMAI</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">15</td><td><strong>FAYA NURANI /</strong></td><td>JL. SINTUK III NO. 8</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">16</td><td><strong>RIZANI NOOR, H / HIDAYATI, HJ</strong></td><td>JL SINTUK III NO 26</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">17</td><td><strong>HAMDAH, HJ / MUHAMMAD RIZKY NAZARUDDIN</strong></td><td>JL SINTUK III NO.29</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">18</td><td><strong>KOSASIH / RETNA HAPSARI KARTADIPURA, IR. MT</strong></td><td>JL SINTUK III NO 22</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">19</td><td><strong>GUPRANSYAH / HERLIANI</strong></td><td>JL SINTUK III NO.36</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">20</td><td><strong>KIOS SEMBAKO (KASNO)</strong></td><td>JALAN SINTUK III NO 15</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">21</td><td><strong>JL. SINTUK III NO. 5</strong></td><td>14 /</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">22</td><td><strong>FIRDAUS SAJELI /</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">23</td><td><strong>RICKY FIRDAUS / PUTRI AYU SOLEHA</strong></td><td>JL SINTUK III NO 26</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">24</td><td><strong>ERMA YUNITA / ERSA FAIRUZA</strong></td><td>JL. SINTUK III NO.30 KOMP.BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">25</td><td><strong>YUNI HAIYIM / ZURAIDAH FATMAWATI</strong></td><td>JL SINTUK III NO 24</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">26</td><td><strong>DENNY AGUSTINA YUNIARTI / DWIKI ADITYA RIADY</strong></td><td>JL SINTUK III NO.20</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">27</td><td><strong>DIAN MUCHTIANINGRUM / ARBILLA NADHIFA PUTRI</strong></td><td>JL. SINTUK III NO.9 KOMP. BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">28</td><td><strong>SURIANSYAH / RAINA YUNIARTI</strong></td><td>JL SINTUK III NO. 30</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">29</td><td><strong>RENTAL MOBIL (YUDHIANTO)</strong></td><td>JALAN SINTUK III NO 7</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">30</td><td><strong>HARIJAWATI / CINDY ISABEL RIANI</strong></td><td>JL. SINTUK III NO 12 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">31</td><td><strong>JL SINTUK III NO 18</strong></td><td>27 /</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">32</td><td><strong>SYAFRUDIN NOOR / SITI ZAINAB</strong></td><td>KOMP. BANJAR INDAH PERMAI JL. SINTUK III NO.16</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">33</td><td><strong>MARSUDI / INDRIYATI RAHMI</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">34</td><td><strong>KASNU / SAMINI</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">35</td><td><strong>FITRI EKA SUMITRA. ST /</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">36</td><td><strong>MAYCKEL HANNY MANUMPAHI / RELIPUNG</strong></td><td>JL SINTUK III NO 2A</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">37</td><td><strong>BARRY SUBANDRI MARBUN, SH / PUTRI GEMI TRI HASTUTI, A.MD</strong></td><td>JL SINTUK III NO 03 KOMP BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">38</td><td><strong>SUPARMO / WELASATININGSIH</strong></td><td>JL SINTUK III NO 9</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">39</td><td><strong>SUKMADJAYA HERMANTO HALIM, LIM / RITA DJAJA</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">40</td><td><strong>MIRDANI, H / MASTIAH, HJ</strong></td><td>JL SINTUK III NO. 13</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">41</td><td><strong>JL. SINTUK III NO 17</strong></td><td>8 /</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">42</td><td><strong>SITI ROFIAH, HJ / NOOR SITI</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">43</td><td><strong>M. RUSLI / ARMANIAH</strong></td><td>JL. SINTUK III NO. 23 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">44</td><td><strong>AHMAD YULIANTO / IDA WINANDARI</strong></td><td>JL SINTUK III NO. 35</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">45</td><td><strong>BANGUNAN KOSONG</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">46</td><td><strong>SITI ZAINAB</strong></td><td>JL. SINTUK III NO.16</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">47</td><td><strong>RIDHO ILHAM UTAMA</strong></td><td>JL SINTUK II</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">48</td><td><strong>LISIEYANA</strong></td><td>JL. UTAN KAYU I NO.79</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">49</td><td><strong>MULIANI</strong></td><td>Jalan kayu kuku banjar indah, RT 15/RW 2</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">50</td><td><strong>HENDRA REZKI PERDANA</strong></td><td>JL. UTAN KAYU NO. 83 KOMPLEK BANJAR INDAH PERMAI</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">51</td><td><strong>JALAN SINTUK II</strong></td><td>4063574</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">52</td><td><strong>MAISYARAH</strong></td><td>Jl. JAMA'AH RT. 15 RW. 001</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">53</td><td><strong>RETNA HAPSARI KARTADIPURA, IR. MT</strong></td><td>JL. SINTUK III NO. 22 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">54</td><td><strong>DAVID IRAWAN</strong></td><td>JL. SINTUK III NO.5</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">55</td><td><strong>GALAMINDO CREATIVE</strong></td><td>JL.SINTUK II NO.168 RT.030 RW.004, PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">56</td><td><strong>Kang T Jang Ing</strong></td><td>Jl Sintuk 1</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">57</td><td><strong>ERICSON M.L GAOL</strong></td><td>JL SINTUK II NO 175</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">58</td><td><strong>NINGTYAS RAHMAWATI, ST, M.SC</strong></td><td>JL. SINTUK III NO.022 KOMP. BANJAR INDAH PERMAI RT.015 RW.002</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">59</td><td><strong>DUTA KARYA ADHITAMA, CV</strong></td><td>JL UTAN KAYU NO 70</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">60</td><td><strong>DEBI CISLINA RAHMAN</strong></td><td>JL. SINTUK I NO.28</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">61</td><td><strong>JL. UTAN KAYU NO 79</strong></td><td>48046218</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">62</td><td><strong>MARGAWATI</strong></td><td>Jl. Sintuk 1</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">63</td><td><strong>CV BERKAT TALENTA MULTIKREASI</strong></td><td>Jl SINTUK 3 NO 32</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">64</td><td><strong>CV. AR-RAZZAQ</strong></td><td>KOMP. BANJAR INDAH PERMAI Jl. SINTUK III NO 20 RT 15</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">65</td><td><strong>SOPIR BOX &lt;BOSMEN&gt;</strong></td><td>JALAN SINTUK III NO 37</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">66</td><td><strong>MARIANA</strong></td><td>JL. AGATIS NO 92</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">67</td><td><strong>SUMARNA, S.PD / MASRIAH, S. PD</strong></td><td>JL LISTRIK INDAH BIP NO 33</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">68</td><td><strong>MUHAMMAD ARIEF / PUTRI RIZKI HANDAYANI</strong></td><td>JL.LISTRIK INDAH KOMP. BANJAR INDAH PERMAI NO.36</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">69</td><td><strong>MEGA ANGGRENI / KARIN CLARISA OEN</strong></td><td>JL RAYA PINANG 3</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">70</td><td><strong>AI MARYATI / MUHAMMAD RIDWAN</strong></td><td>YUDISTIRA V</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">71</td><td><strong>JL AGATIS NO 95 BIP</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">72</td><td><strong>HENDRIK DJAJA / TUSTI HOESIN</strong></td><td>JL UTAN KAYU NO.80</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">73</td><td><strong>NANI / ADAM PERDANA PUTRA</strong></td><td>JL. AGATIS 95</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">74</td><td><strong>PATRICIA LENDA LINO</strong></td><td>JL KASTURI RAYA NO 999F</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">75</td><td><strong>RIZKON NOOR IHWANI / AULIA NISA</strong></td><td>JL. SINTUK III NO.44</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">76</td><td><strong>SAMIDRI / MASNUN</strong></td><td>JL. SINTUK III NO.1 A</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">77</td><td><strong>EKA RUSMITA AGUSTINA / MUHAMMAD NAUFAL PRATAMA</strong></td><td>JL LISTRIK INDAH 23</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">78</td><td><strong>RIF'AN BADI / MULIANI</strong></td><td>JL UTAN KAYU SAMPING LANGGAR B</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">79</td><td><strong>RIZKY EKA SAPUTRA / HESTY UTAMI PUTERI</strong></td><td>JL. LISTRIK INDAH NO. 4</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">80</td><td><strong>HENDRA ARIANSYAH, S.PD / TIETIN KASWARDANA</strong></td><td>JL SINTUK III BIP NO 36</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">81</td><td><strong>JL. SINTUK III NO. 15</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">82</td><td><strong>ZURAIDAH LATIFAH, DRA / HAFIDZ RACHMAN AHMAD RASYID</strong></td><td>JL UTAN KAYU BIP NO 105</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">83</td><td><strong>TEKKU / CHAIHWA</strong></td><td>JL UTAN KAYU NO. 54</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">84</td><td><strong>TARYONO / LEINAWATI</strong></td><td>JL SUKAMARA</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">85</td><td><strong>DISMAS PURBA, SE / TETTY SYAMSIAH HUTAPEA</strong></td><td>JL LISTRIK INDAH NO 34</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">86</td><td><strong>AHMAD SAJALI / DWI HAYATI AHSA</strong></td><td>JL. UTAN KAYU NO. 63 KOMP. BANJAR INDAH PERMAI</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">87</td><td><strong>NUR LAILA HAYATI / GUSTI ADRIAN SETYAWAN</strong></td><td>JL. AGATIS NO. 102</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">88</td><td><strong>BOSMEN SIHOTANG / NOOR ASNAH</strong></td><td>JL SINTUK III NO.37</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">89</td><td><strong>GUSTI AUDINA ANGGRAINI / FAZIA AYRA NAIFA</strong></td><td>JL UTAN KAYU BIP NO 102</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">90</td><td><strong>NGO DJOLIANTO / FENY GUNAWAN</strong></td><td>JL SUNTUK III BIP NO 77</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">91</td><td><strong>JL SUNTUK III BIP NO 22</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">92</td><td><strong>INDRA LIMANTARA / LISIEYANA</strong></td><td>JL.SINTUK III NO.45</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">93</td><td><strong>STEFANUS ERWIN DAUD / GO NOVIA YULIANTI NUGROHO</strong></td><td>JL. LISTRIK INDAH NO.27 KOMP.BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">94</td><td><strong>HERU SUTANTO / RIAWATI</strong></td><td>JL UTAN KAYU NO 52</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">95</td><td><strong>FRENGKY AGUS SUWANTO / SILVIA AGNES ULIANATA</strong></td><td>JL KAYU UTAN NO.57</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">96</td><td><strong>STEVEN / YULIA DAMAYANTI</strong></td><td>KOMPLEK SUKARAMI GARDENA</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">97</td><td><strong>FAHRUL RAZI</strong></td><td>PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">98</td><td><strong>TENDY SUWARDJONO / RETNA MAHANANI KARTADIPURA</strong></td><td>JL UTAN KAYU BIP NO 101</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">99</td><td><strong>LIM HUNG KUANG</strong></td><td>JL UTAN KAYU BIP NO 55</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">100</td><td><strong>OSMAND HASUDUNGAN SIMANJUNTAK</strong></td><td>JL. BANJAR INDAH PERMAI KOMP. LAMPAU PERMATA HIJAU</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">101</td><td><strong>PEMURUS DALAM</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">102</td><td><strong>DEVI AMELINDA AGNES / AZEENA NASYA ZALINA</strong></td><td>JL. LISTRIK INDAH NO.38</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">103</td><td><strong>M. NOOR IRFANSYAH / MUHAMMAD DAFFA DINULLAH</strong></td><td>PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">104</td><td><strong>HADRIYANI / MUNAHAYATI</strong></td><td>JL. BANJAR INDAH KOMP. LAMPAU PERMATA HIJAU NO. 1A</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">105</td><td><strong>SITI NOORHAYATI</strong></td><td>JL LISTRIK INDAH NO 30</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">106</td><td><strong>LANNY SETIAWATY, ONG / BOBBY USMAN</strong></td><td>JL LISTRIK INDAH BIP NO 37</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">107</td><td><strong>HENDY BUDIMAN SUTANTO / MELLISA KURNIAWAN</strong></td><td>KOM. BANJAR INDAH PERMAI. JLN UTAN KAYU. NO 52</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">108</td><td><strong>RUSMAWARDI / NURHAYATI</strong></td><td>JL LISTRIK INDAH BIP NO 46</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">109</td><td><strong>M. RIZKY AULIA RAHMAN / NADIYA RAHMAH</strong></td><td>GG. KARYA INDAH</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">110</td><td><strong>RATNA SRIHANDAYANI / QISYA PUTRI RAHMAN</strong></td><td>JL. NAKULA 2 NO.16</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">111</td><td><strong>KOMP. LAMPAU PERMATA HIJAU NO. 7 BANJAR INDAH PERMAI</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">112</td><td><strong>JONI SETIAWAN LAUW / JUNINGSIH MULIANTON</strong></td><td>JL AGATIS BIP NO94</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">113</td><td><strong>SABIT TOHARI, M.SI / WULANDEWI MARHAENI, DR.SP.A</strong></td><td>JL UTAN KAYU BIP NO 61</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">114</td><td><strong>MARIAWATI / RENALDO HERMAWAN</strong></td><td>JL. UTAN KAYU NO. 69</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">115</td><td><strong>MUHAMMAD ALMAHDI / EKA VERA MIRANTI</strong></td><td>KOMP. LAMPAU PERMATA HIJAU NO.27</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">116</td><td><strong>DHENY HENDRAWAN, SE / SRI INDRAWATI</strong></td><td>JL LISTRIK INDAH NO 56</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">117</td><td><strong>I NYOMAN RIZKI WARDHANA / MAS WAHYU PRIHATIN RIZKIAWATI</strong></td><td>JL RAMIN</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">118</td><td><strong>TONNY / ERNI CHAYANA</strong></td><td>JL SINTUK III NO. 31</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">119</td><td><strong>YUSUF WIJAYA / TENG SIU LIE</strong></td><td>JL. UTAN KAYU NO.63 BANJAR INDAH</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">120</td><td><strong>SRIWATI / MUHAMMAD ALFIAN RAMADHAN</strong></td><td>JL. SEPAKAT PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">121</td><td><strong>JL. AGATIS NO 108</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">122</td><td><strong>JOHNNY SUGIANNOOR / MARLISA KUSwANTO</strong></td><td>JL. BIMA II</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">123</td><td><strong>AULIA BUDHY / FAULYNA</strong></td><td>JL. UTAN KAYU KOMP.LISTRIK INDAH NO.1B BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">124</td><td><strong>FAJRIANSYAH NOOR / MUHAMMAD RIZKY</strong></td><td>JL. SINTUK III NO. 46 KOMP. BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">125</td><td><strong>SITI ZAINAB</strong></td><td>JL UTAN KAYU BIP NO 64</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">126</td><td><strong>GUSTI ERWIN, DRS / GUSTI ADITYA</strong></td><td>JL. UTAN KAYU NO. 51</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">127</td><td><strong>RATNA FAUJIAH, DRA, HJ / AHMAD ALFIN YANUAR NOOR FITRI</strong></td><td>JL. PINANG</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">128</td><td><strong>AKHMAD BE YUDHI PRANATA</strong></td><td>JL. UTAN KAYU NO.58</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">129</td><td><strong>EFFENDI / CHENDRA TANU</strong></td><td>JL.SINTUK III NO.45</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">130</td><td><strong>DJOKO PRAJITNO / LINDA TANU</strong></td><td>KOMP. LAMPAU PERMATA HIJAU NO.A.3 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">131</td><td><strong>JL. SINTUK III NO. 38</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">132</td><td><strong>MICHAEL HADINATA / YESICA LORENSIA</strong></td><td>JL UTAN KAYU BIP NO 69</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">133</td><td><strong>SYAMSUL BAHRI / TUTI SUMIANA</strong></td><td>JL LISTRIK INDAH NO 149</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">134</td><td><strong>HIMAWAN LUFTHI GEOVANNIE / NABILLA ARTINI RACHMAN</strong></td><td>SAWAHAN RT 08 RW 02</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">135</td><td><strong>AHMAD ALFISYAHRIN NOOR FITRI, SST, M.I.KOM / GHINA RAHMATIKA</strong></td><td>JL UTAN KAYU BIP NO 67</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">136</td><td><strong>MUHAMMAD ARMANSYAH / NUR MEILIANA RIZA</strong></td><td>JL UTAN KAYU NO 62 KOMP BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">137</td><td><strong>HARTONO RUSTAN / AY MIE</strong></td><td>JL. UTAN KAYU NO. 71</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">138</td><td><strong>FERRY SETIAWAN / MASDALENA MARPAUNG</strong></td><td>JL. NAKULA NO.23</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">139</td><td><strong>ADE SATRIA / ADINDA NUR RAMADHEANI</strong></td><td>JL LISTRIK INDAH BIP NO 67</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">140</td><td><strong>ROBBY CAHYADI</strong></td><td>JL. SINTUK III NO. 24</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">141</td><td><strong>JL UTAN KAYU BIP NO 53</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">142</td><td><strong>SUKIMAN / SULISTIANI SUPARNI</strong></td><td>JL. AGATIS</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">143</td><td><strong>FERRY SUYONO / MARNI'AH</strong></td><td>JL. UTAN KAYU NO 47</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">144</td><td><strong>INDRIANIE NOOR / SRILAUWATI LAUWU</strong></td><td>KOMP. LAMPAU HIJAU NO 43</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">145</td><td><strong>SUGIYO, IR / SUPARNI</strong></td><td>JL UTAN KAYU NO 68 KOMP BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">146</td><td><strong>YOESANDY DHARMA LIMANTARA, SE. / VANNY SUGIANNOOR, SE.</strong></td><td>JL AGATIS NO 97</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">147</td><td><strong>HARYANTO TRIYADI / YUNITA TJITRADI</strong></td><td>JL PINANG</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">148</td><td><strong>MUHAMMAD RABIUL AWAL GAFFAR / DEWI AGUSTINA SAFETYN</strong></td><td>JL SINTUK III BIP NO 34</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">149</td><td><strong>SARDI HADI YANTO / MURNIWATI SUTANTO</strong></td><td>JL.UTAN KAYU NO 73</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">150</td><td><strong>SUBRIANUR / MAYA ELIYANTI</strong></td><td>JL. SINTUK III NO. 38 BANJAR INDAH PERMAI</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">151</td><td><strong>JL. B.I.P. KOMP. LAMPAU PERMATA HIJAU NO. 14</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">152</td><td><strong>KUSTINAH</strong></td><td>JL LISTRIK INDAH BIP NO 36</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">153</td><td><strong>NOFAL / SRI NORHAYATI</strong></td><td>JL LISTRIK INDAH KOMP BANJAR I</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">154</td><td><strong>RUSMIATI / SELMA RAGILIA</strong></td><td>JL SINTUK II</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">155</td><td><strong>TAUFIQ RIFANI / RAHMI YULIA ARIANI</strong></td><td>JL AGATIS NO 106 BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">156</td><td><strong>HENDRA SUSANTO CITRADI / LISA</strong></td><td>JL. UTAN KAYU NO. 18 KOMP. BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">157</td><td><strong>JULI ASTAN SYAHRONI / QISTHIE NAYA MAULIDA</strong></td><td>PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">158</td><td><strong>ALIP / HENNY NOORANI SURJAPUTERA</strong></td><td>CECATU D2/1A PURIMAS</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">159</td><td><strong>RUSMINAH / WANDI SANYOTA ANTASARI</strong></td><td>JL UTAN KAYU 59</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">160</td><td><strong>RIZALI NOR, S.SOS, H / SITI ASNAH, IR, HJ</strong></td><td>JL UTAN KAYU NO 62 KOMP BIP</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">161</td><td><strong>KOMP. BIP JL. AGATIS NO.94</strong></td><td>-</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">162</td><td><strong>MERLIN, SE</strong></td><td>JL UTAN KAYU NO. 49</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">163</td><td><strong>ZAINAB / MUHAMMAD ERWIN FEBRIAN</strong></td><td>JL UTAN KAYU NO.64</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">164</td><td><strong>MULJADI BAMBANG / RAHMANATHA ZUSIYANA</strong></td><td>JL UTAN KAYU NO. 66</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">165</td><td><strong>DEDI SUTIONO / MARIZKA NOPIANTI</strong></td><td>JL SINTUK III</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">166</td><td><strong>AR-RAZZAQ</strong></td><td>KOMP. BANJAR INDAH PERMAI JL. SINTUK III NO. 20 RT. 15</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">167</td><td><strong>CHENDRA TANU</strong></td><td>JL. UTAN KAYU NO 79</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">168</td><td><strong>LUSIANA</strong></td><td>JL. SINTUK III NO. 5</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">169</td><td><strong>JUANDA DIESEL</strong></td><td>JL.SINTUK III NO.32 RT.036, PEMURUS DALAM</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">170</td><td><strong>RISNAWATI</strong></td><td>JL SINTUK III NO 48</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">171</td><td><strong>JL.SINTUK III NO.11 PEMURUS DALAM, BANJARMASIN SELATAN, KOTA BANJARMASIN</strong></td><td>47025478</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">172</td><td><strong>AFIFAH PUTRI ANANDA</strong></td><td>KOMP. BANJAR INDAH PERMAI JL. SINTUK 3 NO. 16 RT. 15 RW. 02</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">173</td><td><strong>RUPADA KARYA</strong></td><td>Jl. Sintuk III No.22, Komp. Banjar Indah Permai Rt.015 Rw.002</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">174</td><td><strong>PRANSIESKA</strong></td><td>JALAN UTAN KAYU NO 79</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">175</td><td><strong>PERMATA MUSTIKA ABADI</strong></td><td>KOMPLEK BANJAR INDAH PERMAI JL SINTUK I</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">176</td><td><strong>GILBERTUS SERA</strong></td><td>JL. SINTUK III NO. 40</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">177</td><td><strong>YUNI HAIYIM</strong></td><td>JL. SINTUK III</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">178</td><td><strong>MUHAMMAD HASBI RAMADHAN</strong></td><td>JALAN SINTUK III NO 26</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                    <tr><td class="text-center">179</td><td><strong>ZULFAN NOOR FAJAR SURYA, S.ST</strong></td><td>KOMP. BANJAR INDAH PERMAI JL. UTAN KAYU NO. 76</td><td class="text-center"><input type="checkbox" class="form-check-input status-chk"></td></tr>
                </tbody>
            </table>
        </div>
    </div>
</div>

<script>
    // Fitur Checkbox Memory (Local Storage)
    document.querySelectorAll('.status-chk').forEach((chk, index) => {
        const row = chk.closest('tr');
        const storageKey = 'pencacahan_rt15_idx_' + index;
        
        if (localStorage.getItem(storageKey) === 'true') {
            chk.checked = true;
            row.classList.add('checked-row');
        }

        chk.addEventListener('change', function() {
            if (this.checked) {
                row.classList.add('checked-row');
                localStorage.setItem(storageKey, 'true');
            } else {
                row.classList.remove('checked-row');
                localStorage.setItem(storageKey, 'false');
            }
        });
    });

    // Fitur Live Search Bar Nyata
    document.getElementById('searchInput').addEventListener('keyup', function() {
        const query = this.value.toLowerCase();
        document.querySelectorAll('#tableBody tr').forEach(row => {
            const text = row.innerText.toLowerCase();
            row.style.display = text.includes(query) ? '' : 'none';
        });
    });
</script>
</body>
</html>
