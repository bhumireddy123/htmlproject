# htmlproject
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="tourism.css">
</head>

<body>



    <div id="sectionmainpage">
        <div class="top">
            <div class="navbar">
                <a href="#" class="logo">TOURISM</a>
                <ul>
                    <li><a href="#" onclick="display('sectionHome')">Home</a></li>
                    <li><a href="#">About us</a></li>
                    <li><a href="#">Contact us</a></li>
                    <li><a href="#">Help</a></li>
                </ul>
            </div>
            <div class="content">
                <h1>Plan Your Trip</h1>
                <p>You must Go on Advantures To <br> Findout where you Truly belong.</p>
                <div>
                    <button onclick="display('sectionHome')"><span></span> LOGIN</button>
                    <button onclick="display('sectionform')"><span></span> REGISTER</button>
                </div>
            </div>
        </div>


        <section class="footer">

            <div class="box-container">
                <div class="box">
                    <h3>quick links</h3>
                    <a href="#">Home</a>
                    <a href="#">about</a>
                    <a href="#">products</a>
                </div>
                <div class="box">
                    <h3>More links</h3>
                    <a href="#">My account</a>
                    <a href="#">my order</a>
                    <a href="#">my favourite</a>
                </div>
                <div class="box">
                    <h3>Locations</h3>
                    <a href="#">Andhrapradesh</a>
                    <a href="#">Telangana</a>
                    <a href="#">Bangalore</a>
                </div>
                <div class="box">
                    <h3>contact info</h3>
                    <a href="#">+999-888-7772</a>
                    <a href="#">test@gmai.com</a>
                    <a href="#">Hyderabad -Telangana</a>

                </div>

                <div class="credit">created by LPU STUDENT | all right reserved</div>
            </div>

        </section>
    </div>


    <div id="sectionHome">
        <div class="bg-container d-flex flex-column justify-content-center">
            <div class="tourism-card">
                <h1 class="main-heading">TOURISM</h1>
                <p class="paragraph">Plan your trip.</p>
                <button class="buttonHome" onclick="display('sectionFavouritePlaces')">GET STARTED</button>
                <button class="buttonHome" onclick="display('sectionmainpage')">BACK</button>
            </div>
        </div>
    </div>


    <div id="sectionFavouritePlaces">
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Some of The Tourist Places</h1>


            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectiontirumalaDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">TIRUMALA</h1>
                    <p class="favourite-place-card-description">
                        And seven heads are named as Seshadri, Neeladri, Garudadri, Anjanadri, Vrushabadri, Narayanadri and Venkatadri.
                        The first hill is known as Vrushabadri. In Kruthayuga, near Thumbura Theertha in Tirumala there lived a demon named Vrushabhasura who was a devotee of Lord Siva.
                    </p>
                </div>
                <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\tirumala4.jpg" class="favourite-place-card-image" />
            </div>


            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">TAJ MAHAL</h1>
                    <p class="favourite-place-card-description">
                        Taj Mahal is the most amazing Mughal architecture and is a famous tourist destination in the world.
                        The place which has been declared as a world heritage site by UNESCO in 1983 is one of the most admired architectures of India’s heritage.
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png" class="favourite-place-card-image" />
            </div>


            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionGoldenTempleDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">GOLDEN TEMPLE</h1>
                    <p class="favourite-place-card-description">
                        It is also called the Durbār Sahib (ਦਰਬਾਰ ਸਾਹਿਬ), which means "sacred audience", as well as the Golden Temple for its gold leaf-covered sanctum centre.
                        The word "Harmandir" is composed of two words: "Hari", which scholars translate as "God ", and "mandir", which means "house". "
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png" class="favourite-place-card-image" />
            </div>


            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionmysorepalacedetailedview')">
                <div>
                    <h1 class="favourite-place-card-heading">MYSORE PALACE</h1>
                    <p class="favourite-place-card-description">
                        The Amba Vilas Palace, also known as Mysore Palace, was once the seat of the Kingdom of Mysore . The palace was also the residence of the royal family, the Wodeyar dynasty.
                        Today, the grand home of the erstwhile rulers of Mysore is one of the most popular tourist attractions in India.
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png" class="favourite-place-card-image" />
            </div>


            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionvaranasiDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">VARANASI TEMPLE</h1>
                    <p class="favourite-place-card-description">
                        See Article History. Alternative Titles: Banaras, Benares, Kashi. Varanasi, also called Benares, Banaras, or Kashi, city, southeastern Uttar Pradesh state, northern India.
                        It is located on the left bank of the Ganges (Ganga) River and is one of the seven sacred cities of Hinduism.
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png" class="favourite-place-card-image" />
            </div>




            <button class="btn btn-dark buttonHome" onclick="display('sectionHome')">BACK</button>
        </div>
    </div>




    <div id="sectionTajMahalDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">VIEW OF TAJ MAHAL</h1>
            <div class="detailed-view-card-container">
                <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">TAJ MAHAL</h1>
                    <p class="detailed-view-card-description">
                        The Taj Mahal is considered to be the greatest architectural achievement
                        in the whole range of Indo-Islamic architecture. Its recognised
                        architectonic beauty has a rhythmic combination of solids and voids,
                        concave and convex and light shadow; such as arches and domes further
                        increases the aesthetic aspect. Not a piece of architecture, as other
                        buildings are, but the proud passions of an emperor's love wrought in
                        living stones.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>Taj Mahal is a white marble mausoleum built by Mughal Emperor, Shah Jahan in the year 1653.</li>
                        <li> Taj Mahal is built in the loving memory of Mumtaz Mahal, wife of Emperor Shah Jahan.</li>
                        <li> Taj Mahal is built by 20000 artisans in a span of 22 years. </li>
                        <li> Taj Mahal is located in Agra near the river Yamuna. </li>
                        <li> Taj Mahal has been chosen as the Seven Wonders of the World. </li>
                        <li> Taj Mahal is surrounded by attractive lawns, trees, and beatiful lakes. </li>
                        <li> Taj Mahal is frequently visited by millions of tourists every year.</li>
                        <li> Taj Mahal is a beautiful monument that has the influence on Islamic Indian and Persian architecture.</li>
                        <li> Taj Mahal has been listed to the UNESCO World Heritage site in the year 1983.</li>
                        <li> Taj Mahal has actual tombs of Mumtaz Mahal and Shah Jahan at the lower level.</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark buttonHome" onclick="display('sectionFavouritePlaces')">
                BACK
            </button>
        </div>
    </div>


    <div id="sectionGoldenTempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">VIEW OF GOLDEN TEMPLE</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">GOLDEN TEMPLE</h1>
                    <p class="detailed-view-card-description">
                        India is a very ancient country that has the most diversified culture, customs, and heritage. It is home to various traditions and religions.
                        Brotherhood and fraternity is the common thread that holds such a diversified population together and instils in them a sense of unity.
                        India is a secular state. In other words, there is no state religion. It respects every religion and does not interfere in the rituals unless it is against public health and morality.
                        It is the legal right of every individual in India to practise, profess, and believe in their chosen religion.There is no discrimination between individuals based on faith.
                        However, most of the Indian population follows Hinduism’s religion, followed by Islam, Christianity, and Sikhism. Many people also practise Buddhism and Jainism.
                        One of the most significant advantages of being an old country is heritage and cultural practices. The Golden Temple is one such heritage site that was built by the Sikhs.
                        Enhance your vocabulary and writing skills with 10 Lines Essays available. Spark up the creativity in you and access various Topics on 10 Lines all in one place.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>Jallianwala Bagh</li>
                        <li>Wagah Border</li>
                        <li>Harike Wetland</li>
                        <li>Bathinda Fort</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark buttonHome" onclick="display('sectionFavouritePlaces')">
                BACK
            </button>
        </div>
    </div>


    <div id="sectionmysorepalacedetailedview">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">VIEW OF MYSORE PALACE</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\mysore1.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\mysore2.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\mysore4.jpg" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">MYSORE PALACE</h1>
                    <p class="detailed-view-card-description">
                        Mysore Palace, also called Amba Vilas Palace, is one of the most magnificent and largest palaces in India.
                        Situated in the southern state of Karnataka, it used to be the official residence of the Wodeyar Dynasty, the rulers of Mysore from 1399 to 1950.
                        The grand palace stands tall in the heart of Mysore city and attracts visitors from across the world.
                        Being one of the prime attractions in India after the Taj Mahal, it certainly deserves a place in every traveler’s bucket list.
                        So why not visit Mysore Palace this holiday season?
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>The Gombe Thotti or Doll’s Pavilion, a collection of traditional dolls</li>
                        <li>Golden Howdah, the Maharaja’s elephant seat made of 85 kilograms of gold</li>
                        <li>Kalyana Mantap or Marriage Pavilion, an octagonal shaped hall with stained glass ceiling</li>
                        <li>Public Durbar Hall, a large hall from where the Maharajas used to address the public</li>
                        <li>Ambavilasa, a beautifully designed hall which was used by the Maharajas for their private audience</li>
                        <li>Elephant Gate or Ane Bagilu, the brass gate which serves as the main entrance to the palace</li>
                        <li>Paintings of Dasara Procession</li>
                        <li>Portrait Gallery, a collection of valuable paintings and photographs of the Royal Family</li>
                        <li>Casket Room containing royal collections</li>
                        <li>Wrestling Courtyard</li>
                        <li>Temples inside the palace</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark buttonHome" onclick="display('sectionFavouritePlaces')">
                BACK
            </button>
        </div>
    </div>


    <div id="sectionvaranasiDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">VIEW OF VARANASI</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\varanasi2.jpeg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\varanasi3.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\varanasi5.jpg" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">VARANASI</h1>
                    <p class="detailed-view-card-description">
                        Varanasi district is a district in the north Indian state of Uttar Pradesh, with Varanasi city as the district headquarters.
                        It is also called Kashi. According to Hindu and Buddhist mythologies, it is one of the sacred places of pilgrimage for Hindus and Buddhists.
                        It is believed that Lord Shiva along with Parvathi as Vishwanatha and Vishalaakshi reside there to bless devotees.
                        Varanasi, also called Benares, Banaras, or Kashi, city, southeastern Uttar Pradesh state, northern India.
                        It is located on the left bank of the Ganges (Ganga) River and is one of the seven sacred cities of Hinduism.
                        Varanasi: “Count the sand of the huge Ganga  those many Indras; The only one Endless is the Ishwara!…,”
                        proclaimed Appar, one of the three great Shaivite Tamil poets from the 7th-8th centuries. Since Adi Shankara,
                        there has been a steady stream of Shaivite Tamils arriving at Kashi to seek Shiva’s “unconditional bliss”.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>New Vishwanath Temple</li>
                        <li>Kashi Vishwanath Temple</li>
                        <li>Durga Temple</li>
                        <li>Alamgir Mosque</li>
                        <li>Manikarnika Ghat</li>
                        <li>Manmandir Ghat</li>
                        <li>Ramnagar Fort</li>
                        <li>Gyan Vapi Well</li>
                        <li>Assi Ghat</li>
                        <li>Dashashwamedh Ghat</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark buttonHome" onclick="display('sectionFavouritePlaces')">
                BACK
            </button>
        </div>
    </div>


    <div id="sectiontirumalaDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">VIEW OF TIRUMALA</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\tirumala5.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\tirumala4.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="C:\Users\sudharshan Reddy\OneDrive\Pictures\project\tirumala6.jpg" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">TIRUMALA</h1>
                    <p class="detailed-view-card-description">
                        Tirumala is located 3,200 feet (980 m) above sea level and covers an area of approximately 10.33 square miles.
                        In ancient literature, Tirupathi is mentioned as Aadhi Varaha kshetra. The Puranas associate the site with Lord Varaha,
                        one of the Avatar of Lord Vishnu. The Varaha shrine is said to be older than the main sanctum of Venkateswara.
                        The origins of the Tirumala Hills lies in a contest between Vaayu (God of Wind) and Adisesha(the first serpent).
                        During Dwapara Yuga, Adisesha blocked Vayu from entering Vaikuntam as Lord Vishnu was in the company of His consort, Lakshmi.
                        An incensed Vayu challenged Adisesha to a fight to decide the stronger between them, Vayu was tasked with trying to blow off Adisesha-
                        from the Holy Meru mountain while Adisesha was asked to protect the peak with his hood. After a long time, Vayu appeared to yield and Adisesha-
                        lifted his hoods assuming that he had won the contest. Vayu then blew away one of the peaks. The peak landed near the Swarnamukhi river and is currently known as Seshachalam hill.
                        A variant to the legend is that the contest created pandemonium on earth and Brahma, Indra and other gods pleaded with Adisesha to relent.
                        When Adisesha obliged, the peak (Ananda hill) and Adisesha were blown off Meru and landed near the banks of river Swarnamukhi. When Adisesha was dejected with his defeat,
                        the Gods converted Adisesha into the seven hills with the hood named as Seshadri hill or Seshachalam hill or Venkatadri hill. Another variant to the story is: Adisesha,
                        fatigued by the contest was instructed by Lord Venkateswara to rest on Earth in a place that he chose for his stay in Kali Yuga
                        The seven peaks of the shrine represent seven heads of Adisesha. Tirumala is one of the 108 Divya Desams
                        And seven heads are named as Seshadri, Neeladri, Garudadri, Anjanadri, Vrushabadri, Narayanadri and Venkatadri.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>The Iconic Temple of Tirupati</li>
                        <li>The Solid Rock Formation — Sila Thoranam</li>
                        <li>The Holy Feet of the Lord — Srivari Paadalu</li>
                        <li>The Sacred Waterfall — Akasa Ganga</li>
                        <li>The Thrilling Joyride — Sri Venkateswara Wildlife Sanctuary</li>
                        <li>The Marvelous Waterstream — Talakona Waterfalls</li>
                        <li>The Healing Waterstream — Papa Vinasam</li>
                        <li>The Legendary Water Body — Chakra Theertham</li>
                        <li>The True Masterpiece — Tumburu Theertham</li>
                        <li>The Famous Shive Kshetra — Srikalahasti
                        </li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark buttonHome" onclick="display('sectionFavouritePlaces')">
                BACK
            </button>
        </div>
    </div>

    <div id="sectionform">
        <section class="form-bg-container">
            <div class="form-container">
                <h1 class="form-h1">login form</h1>
                <form action="#">
                    <div class="control">
                        <label for="name">Name:</label>
                        <input type="text" name="'name" id="name">
                    </div>

                    <div class="control">
                        <label for="psw">Password:</label>
                        <input type="password" name="'psw" id="psw">
                    </div>


                    <div class="link">
                        <button class="form-button btn btn-dark" onclick="display('sectionmainpage')">LOGIN</button>
                    </div>
                    <br>
                    <br>
                    <div class="link">
                        <a href="#">Forgot Password ?</a>
                    </div>
            </div>
        </section>
    </div>


    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>


#html.css project
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');


.top {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goa-c2-img.png");
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
}

.navbar {
    width: 85%;
    margin: auto;
    padding: 30px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;
}

.logo {
    font-size: 40px;
    font-weight: bolder;
    cursor: pointer;
    text-decoration: none;
    color: white;
    font-family: "Bodoni Mt Black";
}

.navbar ul li {
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
    font-family: "Algerian";
}

.navbar ul li a {
    text-decoration: none;
    color: white;
    font-size: 20px;
}

.navbar ul li::after {
    content: '';
    height: 3px;
    width: 0;
    background: white;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.6s;

}

.navbar ul li:hover::after {
    width: 100%;
}

.content {
    width: 100%;
    color: white;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
    font-family: "Algerian";
}

.content h1 {
    margin-top: 80px;
    font-size: 70px;
}

.content p {
    margin-top: 20px auto;
    line-height: 25px;
    font-size: 25px;
}

button {
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    border-radius: 25px;
    border: 1px solid skyblue;

    background: transparent;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    color: white;
}

span {
    position: absolute;
    left: 0;
    top: 0;
    background-color: black;
    width: 0;
    height: 100%;
    border-radius: 25px;
    z-index: -1;
    transition: 0.5s;

}

button:hover span {
    width: 100%;
}

button:hover {
    border: none;
}

.footer {
    padding: 20px 9%;
    text-transform: capitalize;
    transition: 0.2s linear;
    text-decoration: none;
    font-family: Verdana, Geneva, Tahoma, sans-serif;

}

.footer .box-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
}

.footer .box-container .box {
    flex: 1 1 250px;

}


.footer .box-container .box h3 {
    color: #333;
    font-size: 25px;
    padding: 10px 0;

}

.footer .box-container .box a {
    display: block;
    color: #666;
    font-size: 15px;
    padding: 10px 0;
    text-decoration: none;

}

.footer .box-container .box a:hover {
    text-decoration: underline;
    color: #e84393;

}

.footer .credit {
    text-align: center;
    padding-left: 30%;
    margin-top: 15px;
    padding-top: 25px;
    font-size: 20px;
    color: #333;
    border-top: 1ps solid rgba(0, 0, 0, 0.1);
}


.bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
    height: 100vh;
    background-size: cover;
}

.tourism-card {
    text-align: center;
    background-color: white;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    padding: 5px;
}

.buttonHome {
    color: white;
    background-color: #25b1cc;
    width: 138px;
    height: 36px;
    border-width: 0px;
    border-radius: 20px;
    padding: 5px;
    font-family: "algerian";
}

.main-heading {
    font-family: "forte";
}

.paragraph {
    font-family: "forte";
}

.favourite-places-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
    height: 120vh;
    background-size: cover;
    padding: 24px;
}

.favourite-places-heading {
    color: white;
    font-family: "castellar";
    font-size: 28px;
    font-weight: bold;
}

.favourite-place-card-container {
    background-color: white;
    border-radius: 8px;
    padding: 16px;
    margin-bottom: 15px;
}

.favourite-place-card-heading {
    color: #0f0e46;
    font-family: "Algerian";
    font-size: 23px;
    font-weight: bold;
}

.favourite-place-card-description {
    color: #6c6b70;
    font-family: "calibri";
    font-size: 13px;
}

.favourite-place-card-image {
    width: 80px;
    height: 100px;
}

.favourite-place-card-text-container {
    margin-right: 15px;
}

.detailed-view-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
    height: 100vh;
    background-size: cover;
}

.detailed-view-heading {
    color: white;
    font-family: "Caveat";
    font-size: 28px;
    font-weight: bold;
    padding: 24px;
}

.detailed-view-card-container {
    background-color: white;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    margin: 24px;
}

.detailed-view-card-heading {
    color: #0f0e46;
    font-family: "broadway";
    font-size: 23px;
    font-weight: bold;
}

.detailed-view-card-description {
    color: #6c6b70;
    font-family: "elephant";
    font-size: 13px;
}

.detailed-view-card-text-container {
    padding: 16px;
}



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Open Sans";
}

.form-h1 {
    text-transform: uppercase;
    font-size: 2em;
    text-align: center;
    margin-bottom: 2em;
    font-weight: bold;
}


.form-bg-container {
    position: relative;
    height: 100vh;
    width: 100%;
    background-position: center center;
    background-size: cover;
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
}

.form-container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: linear-gradient(rgba(0, 0, 0, 0, 3), rgba(0, 0, 0, 0, 3));
    width: 380px;
    padding: 50px 30px;
    border-radius: 10px;
    box-shadow: 7px 7px 60px #000;
}

.control {
    width: 100%;
    display: block;
    padding: 10px;
    color: #222;
    border: none;
    outline: none;
    margin: 1em 0;
}

.link {
    text-align: center;
}

.form-button {
    padding: 4px;
    border-radius: 10px;
    width: 100px;
    background-color: #fff;
    color: black;
    border: none;
    text-transform: uppercase;
    font-weight: 600;
}
