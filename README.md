# CryptoSlime.github.io
CrytoSlime!

<img src="https://cloudflare-ipfs.com/ipfs/Qmaxdu3tp4TjM57ajBUU2t3TDCxiNF39GCFds2wLm4a7ym" width="15%"></img> 
<img src="https://cloud.githubusercontent.com/assets/4307137/10105290/2a183f3a-63ae-11e5-9380-50d9f6d8afd6.png" width="18%"></img> 
<img src="https://cloud.githubusercontent.com/assets/4307137/10105284/26aa7ad4-63ae-11e5-88b7-bc523a095c9f.png" width="18%"></img> 
<img src="https://cloud.githubusercontent.com/assets/4307137/10105288/28698fae-63ae-11e5-8ba7-a62360a8e8a7.png" width="18%"></img> 
<img src="https://cloud.githubusercontent.com/assets/4307137/10105283/251b6868-63ae-11e5-9918-b789d9d682ec.png" width="18%"></img> 
<img src="https://cloud.githubusercontent.com/assets/4307137/10105290/2a183f3a-63ae-11e5-9380-50d9f6d8afd6.png" width="18%"></img> 


<!doctype html>
<html>

<head>
    <title>Images gallery</title>
    <meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="CSS/styles.css">
</head>

<body>

    <section id="image-filter-menu">
        <div class="container-fluid filter-buttons">
            <div class="btn-group btn-group-justified">
                <div class="btn-group">
                    <button onclick="filterSeclection('image-box')" type="button" class="btn btn-primary image-box-button">All</button>
                </div>
                <div class="btn-group">
                    <button onclick="filterSeclection('cat1')" type="button" class="btn btn-primary cat1-button">Category 1</button>
                </div>
                <div class="btn-group">
                    <button onclick="filterSeclection('cat2')" type="button" class="btn btn-primary cat2-button">Category 2</button>
                </div>
                <div class="btn-group">
                    <button onclick="filterSeclection('cat3')" type="button" class="btn btn-primary cat3-button">Category 3</button>
                </div>
                <div class="btn-group">
                    <button onclick="filterSeclection('cat4')" type="button" class="btn btn-primary cat4-button">Category 4</button>
                </div>
                <div class="btn-group">
                    <button onclick="filterSeclection('cat5')" type="button" class="btn btn-primary cat5-button">Category 5</button>
                </div>
            </div>
        </div>

        <div class="container-fluid filter-buttons-dropdown">
            <div class="row">
                <div class="btn-group">
                    <button type="button" class="btn btn-primary image-box-button" style="width:80%" onclick="filterSeclection('image-box')">
                        All
                    </button>
                    <button type="button" class="btn btn-primary dropdown-toggle" style="width:20%" data-toggle="dropdown">
                        <span class="caret"></span>
                    </button>
                    <ul class="dropdown-menu" role="menu">
                        <li>
                            <button type="button" onclick="filterSeclection('cat1')" class="btn btn-primary cat1-button">Category 1</button>
                        </li>
                        <li>
                            <button type="button" onclick="filterSeclection('cat2')" class="btn btn-primary cat2-button">Category 2</button>
                        </li>
                        <li>
                            <button type="button" onclick="filterSeclection('cat3')" class="btn btn-primary cat3-button">Category 3</button>
                        </li>
                        <li>
                            <button type="button" onclick="filterSeclection('cat4')"class="btn btn-primary cat4-button">Category 4</button>
                        </li>
                        <li>
                            <button type="button" onclick="filterSeclection('cat5')" class="btn btn-primary cat5-button">Category 5</button>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>


    <section id="modalSection">
        <div class="container-fluid text-center modal" id="modal">
            <div class="row" style="height:90%">
                <div class="col-sm-12" style="height:100%">
                    <img src="">
                </div>
            </div>
            <div class="row modal-menu">
                <div class="col-xs-3">
                    <span class="glyphicon glyphicon-chevron-left" onclick="displayPrevPhoto()">
                </div>
                <div class="col-xs-2">
                    <span class="glyphicon glyphicon-eye-open additionalOption" onclick="openCurrentImageInNewWindow()">
                </div>
                <div class="col-xs-2">
                    <span class="glyphicon glyphicon-remove-circle" onclick="closeModal()">
                </div>
                <div class="col-xs-2">
                    <span class="glyphicon glyphicon-zoom-in additionalOption">
                </div>
                <div class="col-xs-3">
                    <span class="glyphicon glyphicon-chevron-right" onclick="displayNextPhoto()">
                </div>
            </div>
        </div>
    </section>


    <section id="imagesContainer">
        <div class="container-fluid gallery">
            <div class="flex-container text-center">
                <div id="1" class="image-box cat1" data-index="1">
                    <img src="images/category1/1.jpg">
                </div>
                <div id="2" class="image-box cat5" data-index="1">
                    <img src="images/category5/1.jpg">
                </div>
                <div id="3" class="image-box cat1" data-index="2">
                    <img src="images/category1/2.jpg">
                </div>
                <div id="4" class="image-box cat2" data-index="1">
                    <img src="images/category2/1.jpg">
                </div>
                <div id="5" class="image-box cat3" data-index="1">
                    <img src="images/category3/1.jpg">
                </div>
                <div id="6" class="image-box cat5" data-index="2">
                    <img src="images/category5/2.jpg">
                </div>
                <div id="7" class="image-box cat2" data-index="2">
                    <img src="images/category2/2.jpg">
                </div>
                <div id="8" class="image-box cat4" data-index="1">
                    <img src="images/category4/1.jpg">
                </div>
                <div id="9" class="image-box cat2" data-index="3">
                    <img src="images/category2/3.jpg">
                </div>
                <div id="10" class="image-box cat5" data-index="3">
                    <img src="images/category5/3.jpg">
                </div>
                <div id="11" class="image-box cat3" data-index="2">
                    <img src="images/category3/2.jpg">
                </div>
                <div id="12" class="image-box cat1" data-index="3">
                    <img src="images/category1/3.jpg">
                </div>
                <div id="13" class="image-box cat4" data-index="2">
                    <img src="images/category4/2.jpg">
                </div>
                <div id="14" class="image-box cat3" data-index="3">
                    <img src="images/category3/3.jpg">
                </div>
                <div id="15" class="image-box cat4" data-index="3">
                    <img src="images/category4/3.jpg">
                </div>
                <div id="16" class="image-box cat5" data-index="4">
                    <img src="images/category5/4.jpg">
                </div>
            </div>
        </div>
    </section>
    
    <script src="JS/imageFilter.js" defer="true"></script>
    <footer></footer>
</body>
</html>
