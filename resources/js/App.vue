<template>
    <h5> 3rd Party Instruction </h5>
    <div>
        <div class="row">
            <span class="col-lg-2 col-md-2 col-sm-2 col-xs-2">
                Logistic Instruction
            </span>
            <span class="col-lg-2 col-md-2 col-sm-2 col-xs-2">
                <a href="#" class="btn btn-default">Draft</a>
            </span>
        </div>
        <div class="row">
            <div class="col-lg-10 col-md-10 col-sm-10 col-xs-10">
                <table>
                    <tr>
                        <td>Assigned Vendor</td>
                        <td>Attention Of</td>
                        <td>Quotation No</td>
                        <td>Invoice To</td>
                    </tr>
                    <tr>
                        <td>
                            <div class="w3-dropdown-hover">
                                <button class="w3-button">Amarit & Associates Logistics Co Ltd</button>
                                <div class="w3-dropdown-content w3-bar-block w3-card-4">
                                    <a href="#" class="w3-bar-item w3-button">Amarit & Associates Logistics Co Ltd</a>
                                    <a href="#" class="w3-bar-item w3-button">Company 2</a>
                                    <a href="#" class="w3-bar-item w3-button">Company 3</a>
                                </div>
                            </div>
                        </td>
                        <td><input type="text" class="form-control" placeholder="John Smith" /></td>
                        <td><input type="text" class="form-control" placeholder="ABC-123-01" /></td>
                        <td>
                            <div class="w3-dropdown-hover">
                                <button class="w3-button">Invoice To</button>
                                <div class="w3-dropdown-content w3-bar-block w3-card-4">
                                    <a href="#" class="w3-bar-item w3-button">Mito</a>
                                    <a href="#" class="w3-bar-item w3-button">Apple</a>
                                    <a href="#" class="w3-bar-item w3-button">Samsung</a>
                                </div>
                            </div>
                        </td>
                    </tr>
                </table>
            </div>
            <div class="col-lg-2 col-md-2 col-sm-2 col-xs-2">

            </div>
        </div>
    </div>
    <div>
        <table class="table">
            <thead class="thead-dark">
                <tr>
                <th scope="col">Description</th>
                <th scope="col">Qty</th>
                <th scope="col">UOM</th>
                <th scope="col">Unit Price</th>
                <th scope="col">Discount(%)</th>
                <th scope="col">VAT(%)</th>
                <th scope="col"></th>
                <th scope="col">Currency</th>
                <th scope="col">VAT Amount</th>
                <th scope="col">Sub Total</th>
                <th scope="col">Total</th>
                <th scope="col">Charge to</th>
                <th scope="col"></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><input class = "form-control" placeholder="Description"></td>
                    <td><input class = "form-control" placeholder="Qty"></td>
                    <td>
                        <div class="dropdown">
                            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Qty
                            </button>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                <a class="dropdown-item" href="#">SHP</a>
                                <a class="dropdown-item" href="#">SHP2</a>
                                <a class="dropdown-item" href="#">SHP3</a>
                            </div>
                        </div>
                    </td>
                    <td><input class = "form-control" placeholder="Unit Price"></td>
                    <td>0%</td>
                    <td>0%</td>
                    <td><i class="bi bi-arrow-right"></i></td>
                    <td>
                        <div class="dropdown">
                            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Currensy
                            </button>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                <a class="dropdown-item" href="#">USD</a>
                                <a class="dropdown-item" href="#">AED</a>
                                <a class="dropdown-item" href="#">IDR</a>
                            </div>
                        </div>
                    </td>
                    <td>0.00</td>
                    <td>0.00</td>
                    <td>0.00</td>
                    <td>
                        <div class="dropdown">
                            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Currensy
                            </button>
                            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                <a class="dropdown-item" href="#">A</a>
                                <a class="dropdown-item" href="#">B</a>
                                <a class="dropdown-item" href="#">C</a>
                            </div>
                        </div>
                    </td>
                    <td><a href="#" class="btn btn-default">-</a></td>
                </tr>
            </tbody>
        </table>
    </div>
</template>
  <script>
  export default {
    setup() {

     }
  }
  </script>
