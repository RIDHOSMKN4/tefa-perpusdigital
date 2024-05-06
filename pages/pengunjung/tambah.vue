<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h1 class="text-center my-4">isi buku kunjungan</h1>
                <form> 
                    <div class="mb-3">
                        <input type="text" class="form-control form-control-lg form-select rounded-5" placeholder="nama....">                           
                    </div>
                    <select class="form-control form-control-lg form-select rounded-5">
                        <option value="">keanggotaan.......</option>
                        <option value="siswa">siswa</option>
                        <option value="guru">guru</option>
                        <option value="staf">staf</option>
                        <option value="umum">umum</option>
                    </select>
                </form>
            </div>
            <div class="mb-3 mt-3">
                    <input type="text" class="form-control form-control-lg form-select rounded-5 " placeholder="kelas...(jika memilih ANGGOTA:'SISWA')">                           
                </div>
            </div>
        </div>
        <select class="form-control form-control-lg form-select rounded-5">
            <option value="">keperluan......</option>
            <option value="bacaz">membaca</option>
            <option value="minjam">meminjam</option>
            <option value="mengembalikan">mengembalikan</option>
            <option value="beli">membeli</option>
        </select>
            <button type="submit" class="btn btn-dark  btn-lg rounded-5 px-5 mt-3">KIRIM</button>
</template>