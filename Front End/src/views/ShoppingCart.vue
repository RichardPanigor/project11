<template>
    <div class="cart">
        <HeaderHB />
        <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-left">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/">
                            <i class="fa fa-home"></i> Home
                        </router-link>
                        <span>Shopping Cart</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Shopping Cart Section Begin -->
    <section class="shopping-cart spad">
        <div class="container">
            <div class="row">
                <div class="col-lg-8">
                    <div class="row">
                        <div class="col-lg-12">
                            <div class="cart-table">
                                <table>
                                    <thead>
                                        <tr>
                                            <th>Image</th>
                                            <th class="p-name text-center">Product Name</th>
                                            <th>Price</th>
                                            <th>Action</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td class="cart-pic first-row">
                                                <img src="img/products/phimsi-1.png" />
                                            </td>
                                            <td class="cart-title first-row text-center">
                                                <h5>Totebag HIMSI</h5>
                                            </td>
                                            <td class="p-price first-row">Rp 30.000</td>
                                            <td class="delete-item"><a href="#"><i class="material-icons">
                                              close
                                              </i></a></td>
                                        </tr>
                                        <tr>
                                            <td class="cart-pic first-row">
                                                <img src="img/products/phimsi-7.png" />
                                            </td>
                                            <td class="cart-title first-row text-center">
                                                <h5>T-Shirt Maba</h5>
                                            </td>
                                            <td class="p-price first-row">Rp 80.000</td>
                                            <td class="delete-item"><a href="#"><i class="material-icons">
                                              close
                                              </i></a></td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        <div class="col-lg-8 text-left">
                            <h4 class="mb-4">
                                Informasi Pembeli:
                            </h4>
                            <div class="user-checkout">
                                <form>
                                    <div class="form-group">
                                        <label for="namaLengkap">Nama lengkap</label>
                                        <input type="text" class="form-control" id="namaLengkap" aria-describedby="namaHelp" placeholder="Masukan Nama">
                                    </div>
                                    <div class="form-group">
                                        <label for="namaLengkap">Email Address</label>
                                        <input type="email" class="form-control" id="emailAddress" aria-describedby="emailHelp" placeholder="Masukan Email">
                                    </div>
                                    <div class="form-group">
                                        <label for="namaLengkap">No. HP</label>
                                        <input type="text" class="form-control" id="noHP" aria-describedby="noHPHelp" placeholder="Masukan No. HP">
                                    </div>
                                    <div class="form-group">
                                        <label for="alamatLengkap">Alamat Lengkap</label>
                                        <textarea class="form-control" id="alamatLengkap" rows="3"></textarea>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="row">
                        <div class="col-lg-12 text-left">
                            <div class="proceed-checkout">
                                <ul>
                                    <li class="subtotal">ID Transaction <span>#HB12000</span></li>
                                    <li class="subtotal mt-3">Subtotal <span>Rp 110.000</span></li>
                                    <li class="subtotal mt-3">Ongkos Kirim <span>10%</span></li>
                                    <li class="subtotal mt-3">Total Biaya <span>Rp 120.000</span></li>
                                    <li class="subtotal mt-3">Bank Transfer <span>BNI</span></li>
                                    <li class="subtotal mt-3">No. Rekening <span>2208 1996 1403</span></li>
                                    <li class="subtotal mt-3">Nama Penerima <span>Aurel</span></li>
                                </ul>
                                <router-link to="/success">
                                    <a class="proceed-btn">I ALREADY PAID</a>
                                </router-link>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Shopping Cart Section End -->
        <FooterHB />



    </div>
    
</template>



<script>

import HeaderHB from '@/components/HeaderHB.vue'
import FooterHB from '@/components/FooterHB.vue'


export default {
    name: "ShoppingCart",
    components: {
    // HelloWorld
    HeaderHB,
    FooterHB
}
}

</script>