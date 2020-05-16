Multi SVG Project

# Presentation
[Click here](https://www.youtube.com/watch?v=m9h12tuUqGo)

# Code
### HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" />
    <title>Sydney Opera House</title>
</head>
<body>
    <svg class="house" viewbox="0 0 1200 800"> 
   <!--  sky-->
   <g id="sky" mode="day" onclick="changemode('night')">
    <polygon points="2,254 75,253 112,146 1,5" style="fill:#FAF9E0"/> <!--  sky1-->
    <polygon points="1,5 112,146 166,3" style="fill:#F9F9EC"/> <!--  sky2-->
    <polygon points="164,3 332,2 225,107 73,253" style="fill:#FAF9E0"/><!--  sky3-->
    <polygon points="225,107 466,175 71,254" style="fill:#FAF9E0"/><!--  sky4-->
    <polygon points="225,107 466,175 493,72" style="fill:#F9F9EC"/><!--  sky5-->
    <polygon points="332,2 225,107 493,72" style="fill:#FAF9E0"/><!--  sky6-->
    <polygon points="332,2 493,72 733,63 868,5" style="fill:#F9F9EC"/><!--  sky7-->
    <polygon points="466,175 733,63 840,242" style="fill:#FAF9E0"/><!--  sky8-->
    <polygon points="466,175 493,72 733,63" style="fill:#F9F9EC"/><!--  sky9-->
    <polygon points="733,63 870,5 1094,241" style="fill:#FAF9E0"/><!--  sky10-->
    <polygon points="733,63 840,242 1092,241" style="fill:#F9F9EC"/><!--  sky11-->
    <polygon points="868,5 974,113 1194,3" style="fill:#FAF9E0"/><!--  sky12-->
    <polygon points="1194,3 974,113 1092,241 1199,239" style="fill:#F9F9EC"/><!--  sky13-->
    </g>

        <!--  ocean-->
   <polygon points="2,254 75,253 74,280" style="fill:#00A2E8"/><!--  ocean1-->
   <polygon points="2,254 74,280 1,674" style="fill:#99D9EA"/><!--  ocean2-->
   <polygon points="74,280 287,468 139,573 1,674"style="fill:#60CFFF"/><!--  ocean3-->
   <polygon points="139,573 1,674 369,796" style="fill:#99D9EA"/><!--  ocean4-->
   <polygon points="1,674 369,796 1,798" style="fill:#00A2E8"/><!--  ocean5-->
   <polygon points="287,468 139,573 207,640 412,679" style="fill:#00A2E8"/><!--  ocean6-->
    <polygon points="207,640 412,679 640,720 369,796" style="fill:#73EAFF"/><!--  ocean7-->
     <polygon points="369,796 640,720 783,798" style="fill:#60CFFF"/><!--  ocean8-->
     <polygon points="287,468 412,679 640,720" style="fill:#99D9EA"/><!--  ocean9-->
    <polygon points="640,720 783,798 929,640" style="fill:#00A2E8"/><!--  ocean10-->
   <polygon points="783,798 929,640 1052,717 1200,799" style="fill:#99D9EA"/><!--  ocean11-->
   <polygon points="929,640 1024,525 1052,717"  style="fill:#60CFFF"/><!--  ocean12-->
   <polygon points="1024,525 1052,717 1198,487 1168,476" style="fill:#99D9EA"/><!--  ocean13-->
   <polygon points="1198,487 1052,717 1200,799" style="fill:#60CFFF"/><!--  ocean14-->
   <polygon points="1071,438 1198,487 1199,239" style="fill:#73EAFF"/><!--  ocean15-->
 <polygon points="1092,237 1199,239 1071,438 1026,294" style="fill:#73EAFF"/><!--  ocean16-->
   <polygon points="1026,294 921,378 1071,438" style="fill:#99D9EA"/><!--  ocean17-->
   <polygon points="1096,237 840,242 755,504 921,378" style="fill:#00A2E8"/><!--  ocean18-->
     <polygon points="755,504 921,378 1168,476 1024,525" style="fill:#73EAFF"/><!--  ocean19--> 
 

        <!--   กรอบฐานข้าง+หน้า -->
          <polygon points="75,253 77,280 326,494 322,459" style="fill:#bdb7a9"/>
          <polygon points="322,459 347, 528 384,578 381,616 346,564 326,494" style="fill:#bdb6ac"/>
          <polygon points="384,578 381,616 527,690 528,651" style="fill:#bdb6ac"/>
          <polygon points="528,651 635,676 635,718 524,690" style="fill:#bdb7ab"/>
          <polygon points="635,676 635,718 797,698 797,656" style="fill:#bdb6ac"/>
          <polygon points="797,698 797,656 925,603 926,641" style="fill:#c4bdb5"/>
          <polygon points="925,603 926,641 1007,579 1006,543" style="fill:#cec8bc"/>
          <polygon points="1007,579 1006,543 1022,493 1021,525" style="fill:#d8d5cc"/>
          <polygon points="1022,493 1021,525 1077,503 1081,471" style="fill:#c7c1b5"/>
          
          
         <!--   ฐานหลัง -->
          <polygon points="75,253 466,177 467,203 454,221 435,224 345,221 353,231 366,238 269,255 237,263 243,282 297,336 241,349 221,360 213,369" style="fill:#f3efe3"/>
          <polygon points="466,177 957,383 710,581 350,470 318,372" style="fill:#f3efe3"/>
          <polygon points="634,239 714,393 827,251 802,198 622,160" style="fill:#f3efe3"/>
          <polygon points="371,206 174,268 459,495 928,489" style="fill:#f3efe3"/>
          
          
         <!--   โดมเล็กซ้าย -->
          <polygon points="454,221 435,224 345,221 353,231 366,238 414,232 438,240" style="fill:#c3bcb4"/>
          <polygon points="385,236 367,238 269,255 345,326 241,349 315,413 331,410 332,398 289,371 274,347 354,346 354,326 357,308 360,279" style="fill:#f7f1e5"/>
          <polygon points="269,255 237,263 317,332 345,326" style="fill:#aca69a"/>
          <polygon points="237,263 243,282 299,336 317,332" style="fill:#b2aba1"/>
          <polygon points="354,326 357,308 360,279 385,236 406,255 417,273 397,315 382,370 369,355" style="fill:#c9cac5"/>
          <polygon points="354,326 369,355 359,376 354,346" style="fill:#adaea6"/>
          <polygon points="385,236 406,255 417,273 438,240 414,232" style="fill:#f6eee3"/>
          <polygon points="221,360 213,369 322,459 347,528 384,578 432,602 538,575 430,588 321,443" style="fill:#a49d93"/>
          <polygon points="432,602 538,575 565,570 617,553 643,543 667,530 667,490 724,507 733,509 757,514 774,514 779,519 801,519 858,504 912,476 918,474 949,450 975,417 972,410 971,397 960,394 960,389 960,383 1068,431 1081,471 1022,493 1006,543 925,603 797,656 635,676 528,651" style="fill:#f8f2e6"/>
          <polygon points="565,570 565,540 594,519 595,560" style="fill:#bab4a4"/>
          <polygon points="594,519 644,503 643,491 667,490 667,530 643,543 617,553 595,560" style="fill:#c5beae"/>
          <polygon points="643,491 644,503 597,518 626,499" style="fill:#a69d96"/>
          <polygon points="597,518 626,499 468,534 469,544" style="fill:#99928c"/>
          <polygon points="432,529 433,536 468,534 626,499 625,493" style="fill:#918d82"/>
          <polygon points="626,499 625,493 638,468 660,477 667,490" style="fill:#c3bca9"/>
          <polygon points="638,468 625,493 432,529 433,536 468,534 469,544 594,519 565,540 565,570 538,575 430,588 327,451 221,360 241,349 315,413 331,410 332,398 289,371 274,347 354,346 359,376 364,380 373,402 370,426 368,443 373,460 384,462 395,472 395,479 400,481 410,482 440,497 456,498 462,509" style="fill:#b2aea5"/>
          <polygon points="462,509 458,501 492,498 522,494 545,491 568,485 592,480 610,475 634,466 654,456 654,459 638,468 569,493 524,502" style="fill:#867f75"/>
          <polygon points="654,459 660,477 638,468" style="fill:#d8d2c2"/>
          <polygon points="440,497 453,471 474,455 477,465 471,466 455,493 462,509 457,501" style="fill:#626258"/>
          <polygon points="471,466 477,465 486,485 470,485 461,481" style="fill:#8e8e86"/>
          <polygon points="461,481 470,485 486,485 492,498 458,501 455,493" style="fill:#b5b6ae"/>
          <polygon points="492,498 522,494 510,475 496,483 496,483 486,485" style="fill:#b6af9f"/>
          <polygon points="510,475 496,483 486,485 477,465 505,466" style="fill:#7f7b70"/>
          <polygon points="505,466 477,465 474,455 509,432 525,420 527,450 505,453" style="fill:#80796f"/>
          <polygon points="505,453 529,450 532,463 527,467 505,466" style="fill:#868580"/>
          <polygon points="505,466 510,475 527,467" style="fill:#7d8079"/>
          <polygon points="510,475 527,467 532,463 545,491 522,494" style="fill:#b2b3ab"/>
          <polygon points="529,450 532,463 555,449" style="fill:#868276"/>
          <polygon points="555,449 532,463 564,473" style="fill:#989488"/>
          <polygon points="532,463 564,473 568,485 545,491" style="fill:#a8a292"/>
          <polygon points="555,449 564,473 580,458 574,442" style="fill:#b8baaf"/>
          <polygon points="580,458 564,473 568,485 592,480" style="fill:#b7b9ae"/>
          <polygon points="525,420 527,450 555,449 555,404" style="fill:#8b8b83"/>
          <polygon points="555,404 555,449 574,442 577,402" style="fill:#868277"/>
          <polygon points="577,402 574,442 590,438 591,408" style="fill:#868580"/>
          <polygon points="590,438 574,442 580,458 594,447" style="fill:#b3b09f"/>
          <polygon points="594,447 580,458 592,480 610,475" style="fill:#b3ad9f"/>
          <polygon points="590,438 594,447 614,436" style="fill:#b5b5ab"/>
          <polygon points="594,447 614,436 634,466 610,475" style="fill:#b8b9b1"/>
          <polygon points="614,436 634,466 654,456 646,449" style="fill:#bcb6a6"/>
          <polygon points="614,436 646,449 638,439 617,428" style="fill:#f9f3e3"/>
          <polygon points="591,408 617,428 614,436 590,438" style="fill:#6e6a5e"/>
          <polygon points="555,404 543,378 525,365 548,370 568,381 617,428" style="fill:#fefffd"/>
          <polygon points="543,378 504,378 502,403 525,420 555,404" style="fill:#e0e1db"/>
          <polygon points="502,403 525,420 507,433" style="fill:#d2d3cd"/>
          <polygon points="502,403 504,378 482,396" style="fill:#d3d4cf"/>
          <polygon points="504,378 525,365 543,378" style="fill:#ddded8"/>
          <polygon points="440,497 453,471 507,433 502,403 482,396 484,383 453,423" style="fill:#c7c8c3"/>
          <polygon points="484,383 482,396 525,365 510,366" style="fill:#aeb4a8"/>
          <polygon points="440,497 410,482 418,448 443,420 453,423" style="fill:#b0aca1"/>
          <polygon points="443,420 463,402 477,371 509,364 530,359 548,370 510,366 484,383 453,423" style="fill:#8e8f87"/>
          <polygon points="477,371 463,402 443,420 457,385" style="fill:#919187"/>
          <polygon points="418,448 432,413 457,385 443,420" style="fill:#868a7c"/>
          <polygon points="432,413 429,403 418,448" style="fill:#435f50"/>
          <polygon points="432,413 429,403 448,368 457,385" style="fill:#587d6c"/>
          <polygon points="448,368 457,385 477,371 470,338" style="fill:#346754"/>
          <polygon points="477,371 502,347 507,306 470,338" style="fill:#65907d"/>
          <polygon points="477,371 502,347 530,359 509,364" style="fill:#959387"/>
          <polygon points="507,306 502,347 530,359 543,322" style="fill:#41775f"/>
          <polygon points="530,359 543,322 562,343 548,370" style="fill:#608a76"/>
          <polygon points="562,343 548,370 568,381 577,369" style="fill:#386e56"/>
          <polygon points="568,381 577,369 597,409" style="fill:#949182"/>
          <polygon points="507,306 543,322 562,343 577,369 597,409 599,405 599,405 583,365 570,340 557,327 545,317 514,301" style="fill:#939184"/>
          <polygon points="617,428 597,409 599,405 583,365 574,349 550,321 514,301 515,283 536,296 552,305 568,321 579,336 586,349 597,369" style="fill:#ccc6ba"/> 
          <polygon points="514,301 470,338 448,368 429,403 418,448 410,482 400,481 405,437 416,411 436,371 452,345 466,327 515,283" style="fill:#b2b2a6"/> 
          <polygon points="400,481 395,479 397,421 405,393 421,362 430,349 451,318 476,298 493,285 515,283 466,327 452,345 436,371 416,411 405,437" style="fill:#a0a295"/> 
          <polygon points="395,472 384,462 387,420 397,420 397,445" style="fill:#898480"/> 
          <polygon points="387,420 397,421 405,393 421,362 430,349 451,318 493,285 470,283 447,298 416,331" style="fill:#919187"/> 
          <polygon points="470,283 447,298 447,259 472,224" style="fill:#386c56"/> 
          <polygon points="472,224 470,283 486,289 492,285 493,245" style="fill:#638c7a"/> 
          <polygon points="493,245 492,285 515,283" style="fill:#3f6f57"/> 
          <polygon points="481,210 472,224 493,245 515,283 536,296 508,241" style="fill:#8a887b"/> 
          <polygon points="484,192 512,224 521,239 551,304 552,305 536,296 508,241 481,210" style="fill:#cac8b9"/> 
          <polygon points="447,259 447,298 416,331 414,325" style="fill:#577968"/> 
          <polygon points="416,331 414,325 414,335" style="fill:#31523f"/> 
          <polygon points="383,462 373,460 368,443 373,402 364,380 382,370 397,315 417,273 438,240 454,221 467,203 484,192 481,210 472,224 447,259 421,311 414,325 416,331 387,420 395,472" style="fill:#aba79b"/> 
          <polygon points="369,355 359,376 373,402 382,370" style="fill:#aba79b"/> 
        
          
          
          
        <!--   ฝาโดมขวา -->
               <!-----------back phawit----------->
            <polygon points="493,72 511,80 495,113 481,98 " style="fill:#d8d9d3"/>
          <polygon points="511,80 530,100 515,134 495,113 " style="fill:#dce2d8"/>
          <polygon points="530,100 547,128 533,163 515,134 " style="fill:#e5e6e0"/>
          <polygon points="481,98 495,113 487,148 473,132 " style="fill:#c4c6c1"/>
          <polygon points="467,201 473,132 487,148" style="fill:#c4c6c1"/>
          <polygon points="467,201 480,155 478,190" style="fill:#d2d3cd"/>
          <polygon points="487,148 509,157 515,134 495,113" style="fill:#cbccc6"/>
          <polygon points="515,134 509,157 533,163" style="fill:#d4d5cf"/>
            <polygon points="489,194 478,190 487,148 509,157" style="fill:#d4d5cf"/>
          <polygon points="487,148 533,163 513,224 489,194" style="fill:#d4d5cf"/>
          <polygon points="467,201 480,155 478,190 487,148" style="fill:#d2d3cd"/>
          <polygon points="547,128 561,182 533,163 " style="fill:#e4e5df"/>
          <polygon points="513,224 549,252 561,182 533,163" style="fill:#d4d5cf"/>
            <polygon points="530,100 547,128 554,126" style="fill:#fcffff"/>
          <polygon points="547,128 554,126 576,173 561,182 " style="fill:#fcffff"/>
            <polygon points="561,182 576,173 606,183 587,206 " style="fill:#cfceca"/>
          <polygon points="595,215 609,185 606,183 587,206 " style="fill:#9a9488"/>
              <polygon points="561,182 587,206 595,215 593,226 549,252  " style="fill:#cecec6"/>
          <polygon points="727,62 667,100 698,110" style="fill:#cbcac5"/>
          
             <polygon points="621,161 667,100 698,110 677,174" style="fill:#cbcac5"/>
           <polygon points=" 677,174 621,161 609,185 595,215 593,226 641,238 677,174" style="fill:#cbcac5"/>
           <polygon points="593,226 641,238 616,321 581,301" style="fill:#cbcac5"/>
          <polygon points="593,226 549,252 513,224 554,300 581,301" style="fill:#bcb8ad"/>
           <polygon points="605,393 578,331 581,301 616,321" style="fill:#cbcac5"/>
           <polygon points="577,319 554,300 578,331" style="fill:#989687"/>
          <polygon points="581,301 554,300 578,331" style="fill:#b7b5a9"/>
          
               <polygon points="727,62 727,83 704,116 698,110 " style="fill:#cdcbbc"/>
          <polygon points="698,110 704,116 677,179 666,174 " style="fill:#cdc7bb"/>
          <polygon points=" 677,179 666,174 641,238 651,241" style="fill:#bbb9aa"/>
          <polygon points="641,238 651,241 628,310 616,321 " style="fill:#b3b1a2"/>
          <polygon points="616,321 628,310 612,395 605,393  " style="fill:#918e7f"/>
          
          
            <polygon points="727,83 704,116 717,145 738,113 " style="fill:#8d8b7c"/>
          <polygon points="717,145 738,113 754,167 725,184 " style="fill:#8d8b7c"/>
          <polygon points="727,62 727,83 738,113 746,101" style="fill:#cdcbbc"/>
          <polygon points="738,113 746,101 761,161 754,167 " style="fill:#cdcbbc"/>
            <polygon points="713,129 707,184  716,191 725,184 717,145" style="fill:#366c54"/>
          <polygon points="704,116 694,140 713,129 " style="fill:#5c8370"/>
          <polygon points="694,140 713,129 707,184 692,175 " style="fill:#5c8370"/>
        <polygon points="670,193 694,140 692,175 " style="fill:#5c8370"/>
          
            <polygon points="707,184  716,191 706,203 692,175 " style="fill:#e9e7d8"/>
            <polygon points="692,175 670,193 706,203 " style="fill:#bfbdae"/>
            <polygon points="670,193 706,203 672,252 " style="fill:#d0cfbb"/>
            <polygon points="651,241 672,252 670,193 " style="fill:#9d9e8e"/>
            <polygon points="651,241 672,252 655,275 646,258 " style="fill:#b6b3a4"/>
          
            <polygon points="670,193 694,140 692,175 " style="fill:#5c8370"/>
            <polygon points="670,193 694,140 692,175 " style="fill:#5c8370"/>
            <polygon points="670,193 694,140 692,175 " style="fill:#5c8370"/>
          
          
          
        <!--   โดมกลางขวา -->
          <polygon points="665,405 610,395 620,340 660,340" style="fill:#9c9688"/>
           <polygon points="680,410 665,405 660,340 695,360" style="fill:#b5b5a9"/>
          <polygon points="660,340 620,340 645,260 655,275 675,250" style="fill:#a09d8e"/>
          <polygon points="660,340 695,360 725,290 740,255 715,245 675,250" style="fill:#c4c5bf"/>
          <polygon points="740,255 715,245 675,250 705,215 720,190 750,190 760,215" style="fill:#cecfc9"/>
          <polygon points="760,215 795,180 800,160 765,160 750,190" style="fill:#ddded9"/>
          <polygon points="750,190 765,160 735,175 720,190" style="fill:#bec0b5"/>
          <polygon points="795,180 800,160 825,190 840,220 845,255 " style="fill:#e7ddd3"/>
          <polygon points="795,180 790,190 805,205 815,230 820,250 835,250 845,255" style="fill:#999a8c"/>
          <polygon points="725,290 740,250 740,270" style="fill:#4a785e"/>
          <polygon points="740,250 740,270 770,240 760,215" style="fill:#699284"/>
          <polygon points="770,240 785,250 805,210 790,190 760,215" style="fill:#437b60"/>
          <polygon points="785,250 800,255 815,230 810,205 " style="fill:#699284"/>
          <polygon points="800,255 815,230 820,250" style="fill:#437b60"/>
          <!--  BANKโดมขวา  -->
          <polygon points="681,408 705,416 705,366" style="fill:#A0A495"/>
          <polygon points="681,408 695,362 705,366" style="fill:#A0A495"/>
          <polygon points="705,416 705,366 747,364 747,411" style="fill:#999385"/>
          <polygon points="747,364 747,411 761,412" style="fill:#B6B7A9"/>
          <polygon points="747,364 784,381 761,412" style="fill:#BABBAC"/>
          <polygon points="761,412 784,381 803,364 804,370 808,401 808,408" style="fill:#656357"/>
          <polygon points="804,370 808,401 823,408 850,401" style="fill:#BFBFB5"/>
          <polygon points="808,401 808,408 833,415 823,408" style="fill:#767467"/>
          <polygon points="833,415 823,408 876,394 887,399" style="fill:#7B7B71"/>
          <polygon points="804,370 837,369 876,394 850,401" style="fill:#BAB3A3"/>
          <polygon points="837,369 876,394 889,387 863,347" style="fill:#B8BAAF"/>
          <polygon points="887,399 876,394 909,376" style="fill:#666253"/>
          <polygon points="863,347 889,387 909,376 888,336" style="fill:#ACA698"/>
          <polygon points="909,376 888,336 892,334 924,371 " style="fill:#C5C6BE"/>
          <polygon points="892,334 924,371 940,358 899,329" style="fill:#C0BAAA"/>
          <polygon points=" 899,329 940,358 952,348" style="fill:#C5C6BE"/>
          <polygon points="899,329 952,348 952,348" style="fill:#C0BAAA"/>
          <polygon points="899,329 908,329 962,338 952,348" style="fill:#C3C1AF"/>
          <polygon points="803,364 804,370 837,369 839,348 817,352" style="fill:#7E7A71"/>
            <polygon points="839,348 817,352 869,303 863,347" style="fill:#7E7A6E"/>
          <polygon points="839,348 837,369 863,347" style="fill:#898884"/>
          <polygon points="869,303 887,310 888,336 863,347" style="fill:#8C8C82"/>
          <polygon points="869,303 887,310 902,281" style="fill:#8C8980"/>
          <polygon points="887,310 902,281 908,329" style="fill:#8B8C84"/>
            <polygon points="887,310 888,336 892,334 899,329 908,329" style="fill:#A9A798"/>
          <polygon points="902,281 908,329 913,288 " style="fill:#878173"/>
          <polygon points="695,362 705,366 725,333 726,290" style="fill:#A0A495"/>
          <polygon points="705,366 725,333 747,364" style="fill:#C5C6BE"/>
          <polygon points="725,333 750,333 747,364" style="fill:#B2B3AD"/>
            <polygon points="785,354 755,327 750,333 747,364" style="fill:#BABBB5"/>
          <polygon points="747,364 784,381 785,354" style="fill:#BABBB5"/>
          <polygon points="784,381 785,354 817,352 804,370" style="fill:#C7C8C3"/>
          <polygon points="817,352 811,324 844,324" style="fill:#D1D2CC"/>
          <polygon points="755,327 785,354 817,352 811,324" style="fill:#D1D2CC"/>
            <polygon points="844,324 829,298 869,303" style="fill:#E4E5DF"/>
          <polygon points="829,298 869,303 902,281 862,258" style="fill:#F3F4EE"/>
          <polygon points="829,298 862,258 802,270" style="fill:#E8E9E3"/>
          <polygon points="862,258 802,270 824,253 838,254" style="fill:#F3F4EE"/>
          <polygon points="802,270 829,298 786,296" style="fill:#DCDDD7"/>
          <polygon points="786,296 829,298 844,325 811,324" style="fill:#DCDDD7"/>
          <polygon points="786,296 811,324 755,327" style="fill:#B8B9B3"/>
          <polygon points="784,254 806,252 824,253 802,270 764,279" style="fill:#B3B8B1"/>
          <polygon points="764,279 802,270 786,296" style="fill:#B9BCB5"/>
          <polygon points="764,279 744,304 758,303 786,296" style="fill:#A2ACA1"/>
          <polygon points="744,304 758,303 750,333" style="fill:#B4BAB0"/>
          <polygon points="758,303 755,327 786,296" style="fill:#BDBEB8"/>
          <polygon points="758,303 750,333 755,327" style="fill:#BDBEB8"/>
          <polygon points="744,304 750,333 725,333" style="fill:#B4B9B2"/>
          <polygon points="726,290 745,268 744,304 725,333" style="fill:#BDBBAE"/>
          <polygon points="745,268 764,279 744,304" style="fill:#989A8C"/>
          <polygon points="745,268 768,240 784,254 764,279" style="fill:#C4BEB0"/>
        <!-- END BANK   -->
          
        <!--   บันได -->
          <polygon points="802,524 780,520 775,515 754,520 666,500 620,435 660,460 " style="fill:#aaa498"/>
          <polygon points="802,524 870,510 930,470 960,454 980,420 802,513" style="fill:#c8c3b0"/>
          <polygon points="802,514 870,500 930,460 960,440 980,410 930,450 920,460 830,500 802,506" style="fill:#e2dbc9"/>
          <polygon points="802,524 660,460, 653,453 640,440 615,430 680,420 707,425 780,430 777,454 785,460 785,475 790,480 785,490 800,495 800,510" style="fill:#a49e90"/>
          <polygon points="800,495 800,510 890,475 940,445 975,415 970,400 930,435 885,465 " style="fill:#bdb5aa"/>
          <polygon points="800,495 885,465  930,435 970,400 972,410 971,397 960,393 785,490" style="fill:#d2cbb8"/>
          <polygon points="785,490 845,465 900,435 960,393 965,405 960,390 790,480" style="fill:#b6b0a0"/>
          <polygon points="790,480 825,465 890,435 960,393 960,390 959,381 785,475" style="fill:#d3cdbd"/>
          <polygon points="785,475 805,465 870,435 959,381 955,370 780,460" style="fill:#9a918a"/>
          <polygon points="780,460 785,465 850,435 955,370 945,365 777,454" style="fill:#dbd3c8"/>
          <polygon points="777,454 765,465 830,435 945,365 940,360 780,430" style="fill:#a29c90"/>
          <polygon points="805,420 777,454  680,420 615,430 610,395 620,395 670,405 685,410" style="fill:#e8e4d8"/>
          
             <!--   เรือ -->
          <g class="boatred">
              <polygon points="171,438 144,492, 169 500" style="fill:#fb8fff"/>
               <polygon points="144,492 184,504 177,512 " style="fill:#C35814"/>
               <polygon points="184,504 204,518 201,523 192,522 177,512 " style="fill:#AD2D04"/>
               <polygon points="204,518 201,523 168,522 " style="fill:#742D01"/>
               <polygon points="201,523 168,522 168,528 194,530 " style="fill:#898989"/>
               <polygon points="194,530 168,528 168,532" style="fill:#838383"/>
               <polygon points="168,522 131,510 138,516 168,528" style="fill:#898989"/>
               <polygon points="138,516 145,522 168,532 168,528" style="fill:#838383"/>
               <polygon points="143 490 130,505 131,510 141,511 142,505 152,498" style="fill:#B54F04"/>
               <polygon points="152,498 175,505 165,514 142,505" style="fill:#B54F04"/>
               <polygon points="175,505 177,512 166,519 165 514" style="fill:#A5A5A5"/>
               <polygon points="142,505 141,511 166,519 165,514  " style="fill:#A5A5A5"/>
               <polygon points="177,512 181,512 192,522 166,520" style="fill:#A5A5A5"/>
                 </g>
          
          <g class="boatblue">
              <polygon points="171,438 144,492, 169 500" style="fill:#42fcff"/>
               <polygon points="144,492 184,504 177,512 " style="fill:#C35814"/>
               <polygon points="184,504 204,518 201,523 192,522 177,512 " style="fill:#AD2D04"/>
               <polygon points="204,518 201,523 168,522 " style="fill:#742D01"/>
               <polygon points="201,523 168,522 168,528 194,530 " style="fill:#898989"/>
               <polygon points="194,530 168,528 168,532" style="fill:#838383"/>
               <polygon points="168,522 131,510 138,516 168,528" style="fill:#898989"/>
               <polygon points="138,516 145,522 168,532 168,528" style="fill:#838383"/>
               <polygon points="143 490 130,505 131,510 141,511 142,505 152,498" style="fill:#B54F04"/>
               <polygon points="152,498 175,505 165,514 142,505" style="fill:#B54F04"/>
               <polygon points="175,505 177,512 166,519 165 514" style="fill:#A5A5A5"/>
               <polygon points="142,505 141,511 166,519 165,514  " style="fill:#A5A5A5"/>
               <polygon points="177,512 181,512 192,522 166,520" style="fill:#A5A5A5"/>
          </g>
          
            <g class="boatgreen">
              <polygon points="171,438 144,492, 169 500" style="fill:#75ff7c"/>
               <polygon points="144,492 184,504 177,512 " style="fill:#C35814"/>
               <polygon points="184,504 204,518 201,523 192,522 177,512 " style="fill:#AD2D04"/>
               <polygon points="204,518 201,523 168,522 " style="fill:#742D01"/>
               <polygon points="201,523 168,522 168,528 194,530 " style="fill:#898989"/>
               <polygon points="194,530 168,528 168,532" style="fill:#838383"/>
               <polygon points="168,522 131,510 138,516 168,528" style="fill:#898989"/>
               <polygon points="138,516 145,522 168,532 168,528" style="fill:#838383"/>
               <polygon points="143 490 130,505 131,510 141,511 142,505 152,498" style="fill:#B54F04"/>
               <polygon points="152,498 175,505 165,514 142,505" style="fill:#B54F04"/>
               <polygon points="175,505 177,512 166,519 165 514" style="fill:#A5A5A5"/>
               <polygon points="142,505 141,511 166,519 165,514  " style="fill:#A5A5A5"/>
               <polygon points="177,512 181,512 192,522 166,520" style="fill:#A5A5A5"/>
            </g>

            <g class="boatpink">
                <polygon points="171,438 144,492, 169 500" style="fill:pink"/>
                 <polygon points="144,492 184,504 177,512 " style="fill:#C35814"/>
                 <polygon points="184,504 204,518 201,523 192,522 177,512 " style="fill:#AD2D04"/>
                 <polygon points="204,518 201,523 168,522 " style="fill:#742D01"/>
                 <polygon points="201,523 168,522 168,528 194,530 " style="fill:#898989"/>
                 <polygon points="194,530 168,528 168,532" style="fill:#838383"/>
                 <polygon points="168,522 131,510 138,516 168,528" style="fill:#898989"/>
                 <polygon points="138,516 145,522 168,532 168,528" style="fill:#838383"/>
                 <polygon points="143 490 130,505 131,510 141,511 142,505 152,498" style="fill:#B54F04"/>
                 <polygon points="152,498 175,505 165,514 142,505" style="fill:#B54F04"/>
                 <polygon points="175,505 177,512 166,519 165 514" style="fill:#A5A5A5"/>
                 <polygon points="142,505 141,511 166,519 165,514  " style="fill:#A5A5A5"/>
                 <polygon points="177,512 181,512 192,522 166,520" style="fill:#A5A5A5"/>
            </g>

            <g class="boatblack">
                <polygon points="171,438 144,492, 169 500" style="fill:black"/>
                 <polygon points="144,492 184,504 177,512 " style="fill:#C35814"/>
                 <polygon points="184,504 204,518 201,523 192,522 177,512 " style="fill:#AD2D04"/>
                 <polygon points="204,518 201,523 168,522 " style="fill:#742D01"/>
                 <polygon points="201,523 168,522 168,528 194,530 " style="fill:#898989"/>
                 <polygon points="194,530 168,528 168,532" style="fill:#838383"/>
                 <polygon points="168,522 131,510 138,516 168,528" style="fill:#898989"/>
                 <polygon points="138,516 145,522 168,532 168,528" style="fill:#838383"/>
                 <polygon points="143 490 130,505 131,510 141,511 142,505 152,498" style="fill:#B54F04"/>
                 <polygon points="152,498 175,505 165,514 142,505" style="fill:#B54F04"/>
                 <polygon points="175,505 177,512 166,519 165 514" style="fill:#A5A5A5"/>
                 <polygon points="142,505 141,511 166,519 165,514  " style="fill:#A5A5A5"/>
                 <polygon points="177,512 181,512 192,522 166,520" style="fill:#A5A5A5"/>
            </g>

         </svg>     
</body>
</html>

  CSS

body{
    margin: 20px;
  }
  
  .house{
    -webkit-background-size: cover;
    background-size: cover;
    overflow: hidden;
    width: 100vw;
    height: 100vh;
    top:-100;
  }
  
  .boatred{
    position: relative;
    animation: red 1s infinite linear 0.8s alternate;
  }
  
  .boatblue{
    position: relative;
    transform: translate(20vw,30vh);
    animation: blue 1s infinite linear 1.5s alternate;
  }
  .boatgreen{
    position: relative;
    transform: translate(50vw,26vh);
    animation: green 1.5s infinite linear 1.7s alternate;
  }
  .boatpink{
    position: relative;
    transform: translate(-5vw,10vh);
    animation: pink 1s infinite linear 0.3s alternate;
  }
  .boatblack{
    position: relative;
    transform: translate(-10vw,10vh);
    animation: black 2s infinite linear 0.3s alternate;
  }

  @keyframes red{
    0%{ transform: translateY(0vh);}
    100%{ transform: translateY(5vh);}
  }
  
  @keyframes blue{
    0%{ transform: translate(20vw,30vh);}
    100%{ transform: translate(20vw,35vh);}
  }
  
  @keyframes green{
    0%{ transform: translate(50vw,26vh);}
    100%{ transform: translate(45vw,26vh);}
  }

  @keyframes pink{
    0%{ transform: translate(-5vw,10vh);}
    100%{ transform: translate(-5vw,5vh);}
  }

  @keyframes black{
    0%{ transform: translate(5vw,10vh);}
    100%{ transform: translate(10vw,10vh);}
  } 
```
## Members

  
  | | 62070144 |  |  |  |
  | --- | --- | --- | --- | --- |
  | | Phawit Sapthaweekarn |  |   |  |
  
