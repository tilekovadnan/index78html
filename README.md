<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <section class="multi step form">
        <form id="msform">
            <div class="title">
                <h2>Verification Process</h2>
                <P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis quam natus, numquam quo maxime minima repellendus nostrum vero, cumque sunt cum? Fuga sequi quia ratione nam soluta iusto quae suscipit.</P>
            </div>

            <ul id="progressbar">
                <li class="active">Verify Phone</li>
                <li>Upload Documents</li>
                <li>Security Questions</li>
            </ul>
                <fieldest>
                    <h3>Setup your phone</h3>
                    <h6>We will sent you a SMS. Vi je pragramist.</h6>
                <div class="form-row">
                    <div class="form-group col-md-6">
                       <input type="tel" placeholder="+996" id="phone" class="form-control">
                    </div>
                    <div class="form-group">
                         <input type="text" placeholder="708700280" class="form-control">
                    </div>
                </div>

                <div class="done_text">
                    <a href="" class="dov_icon"><i class="ion-android-done"></i></a>
                    <h6>A secret code is sent to your phone. <br>Plase enter it here.</h6>
                </div>

                <div class="code_group">
                     <input type="text" placeholder="0" class="form-control">
                     <input type="text" placeholder="0" class="form-control">
                     <input type="text" placeholder="0" class="form-control">
                     <input type="text" placeholder="0" class="form-control">
                </div>

                <button class="action_button previous_button">Back</button>
                <button class="action_button next">Continue</button>
            </fieldest> 
             
            <fieldest>
                <h3>Verify Your Identity</h3>
                <h6>Please upload any of these documents to verify your Identily</h6>
                <div class="passport">
                    <h4>Govt. ID card <br>PassPort <br>Driving License. </h4>
                    <a href="" class="don_icon"><i class="ion-android-done"></i></a>
                </div>
                <div class="input-group">
                    <div class="custom-file">
                        <input type="file" name="" id="upload" class="custom-file-input">
                        <label for="" class="custom-file-lable"><i class="ion-android-cloud-outline"></i>Choose file</label>
                    </div>
                </div>

                <ul class="file-added">
                    <li>File Added:</li>
                    <li><a href=""><i></i>national_id_card.png</a></li>
                    <li><a href=""><i></i>national_id_card_back.png</a></li>
                </ul>
                <button class="action-button previous previous_button">Back</button>
                <button class="action-button next">Continue</button>
            </fieldest>
            
        </form>
    </section>
</body>
</html>
