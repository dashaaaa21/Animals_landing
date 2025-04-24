<!DOCTYPE html>
<html lang="uk">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Світ Тварин</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;600;700&display=swap&subset=cyrillic" rel="stylesheet">

</head>

<body style="font-family: 'Rubik', sans-serif;">
  <!-- Навігація -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Світ Тварин</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Головна</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Про нас</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Блог</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Контакти</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Секція героя -->
  <div class="bg-light text-center p-5">
    <h1 class="display-4">Ласкаво просимо у світ тварин</h1>
  
    <p class="lead">Пізнавай дику природу разом з нами. Факти, фото і дивовижні історії з усього світу.</p>
    <a href="#why-us" class="btn btn-success btn-lg">Дізнатись більше</a>
  </div>

  <!-- Картки -->
  <div class="container my-5">
    <h2 class="mb-4 text-center">Наші улюбленці</h2>
    <div class="row g-4">
      <div class="col-sm-12 col-md-6 col-lg-6">
        <div class="card text-white">
          <img src="https://img.freepik.com/free-photo/closeup-shot-raccoon-cleaning-its-hand_181624-23233.jpg?t=st=1745485487~exp=1745489087~hmac=8408b7c78f5d4e0acec314823fe9621df63ee6bda91120839e40c74841ec6913&w=1380" class="card-img" alt="Песик">
          <div class="card-img-overlay d-flex flex-column justify-content-end bg-dark bg-opacity-50">
            <h5 class="card-title"> Макс</h5>
            <p class="card-text">Вірний друг і охоронець. Любить бігати та грати з м'ячем.</p>
            <p class="card-text"><small>Оновлено 1 день тому</small></p>
          </div>
        </div>
      </div>

      <div class="col-sm-12 col-md-6 col-lg-6">
        <div class="card text-white">
          <img src="https://img.freepik.com/free-photo/view-funny-animals_23-2151098333.jpg?t=st=1745485507~exp=1745489107~hmac=e02822f742c5b779c58f4df3fac22a93b28b92c57ee0b7a2119e19a456333037&w=1380" class="card-img" alt="Кіт">
          <div class="card-img-overlay d-flex flex-column justify-content-end bg-dark bg-opacity-50">
            <h5 class="card-title"> Луна</h5>
            <p class="card-text">Тиха, граційна й трохи загадкова. Полюбляє спати на сонечку.</p>
            <p class="card-text"><small>Оновлено 3 дні тому</small></p>
          </div>
        </div>
      </div>

      <div class="col-sm-12 col-md-6 col-lg-6">
        <div class="card text-white">
          <img src="https://img.freepik.com/free-photo/giraffe-chewing-plant_1161-175.jpg?t=st=1745485525~exp=1745489125~hmac=9798faca714c976aa9ec39647404317236e946b2080d6826e3138a872362edc2&w=1380" class="card-img" alt="Папуга">
          <div class="card-img-overlay d-flex flex-column justify-content-end bg-dark bg-opacity-50">
            <h5 class="card-title"> Арі</h5>
            <p class="card-text">Говорить, співає, і навіть танцює! Яскравий та веселий друг.</p>
            <p class="card-text"><small>Оновлено тиждень тому</small></p>
          </div>
        </div>
      </div>

      <div class="col-sm-12 col-md-6 col-lg-6">
        <div class="card text-white">
          <img src="https://img.freepik.com/free-photo/duck-nature-generate-image_23-2150632080.jpg?t=st=1745485558~exp=1745489158~hmac=3ffd615c0897c207c4ded70b7d8d080f226b32d5cf54c38a5fc99795fa2f27d1&w=1380" class="card-img" alt="Хом'як">
          <div class="card-img-overlay d-flex flex-column justify-content-end bg-dark bg-opacity-50">
            <h5 class="card-title"> Пафік</h5>
            <p class="card-text">Маленький, пухнастий і дуже жвавий. Любить гризти моркву.</p>
            <p class="card-text"><small>Оновлено 2 години тому</small></p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Чому обирають нас -->
  <div class="container my-5" id="why-us">
    <h2 class="text-center mb-4">Чому обирають нас?</h2>
  <div class="row text-center">
    <div class="col-md-4">
      <div class="card border-0">
        <div class="card-body">
          <h5 class="card-title">Досвід</h5>
          <p class="card-text">10+ років у сфері турботи про тварин. Ми знаємо, як зробити їх щасливими.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card border-0">
        <div class="card-body">
          <h5 class="card-title">Любов до тварин</h5>
          <p class="card-text">Кожен наш співробітник — справжній фанат тварин. Це не просто робота — це покликання!</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card border-0">
        <div class="card-body">
          <h5 class="card-title">Підтримка 24/7</h5>
          <p class="card-text">Маєш питання? Ми завжди на зв'язку, щоб допомогти тобі та твоєму улюбленцю.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Галерея -->
<div class="container my-5">
  <h2 class="text-center mb-4">Галерея наших друзів</h2>
  <div class="row g-3">
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/free-photo/green-lizard-branch-green-lizard-sunbathing-wood-green-lizard-climb-wood-jubata-lizard-closeup_488145-3202.jpg?t=st=1745485916~exp=1745489516~hmac=d17f35613f45f5206944260e95397e3df5f1d82d4d58d35e87a1e92b33e36727&w=826" class="img-fluid rounded" alt="Тварина 1">
    </div>
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/free-photo/vertical-shot-beautiful-deer-standing-forest-with-blurred-background_181624-6271.jpg?t=st=1745485932~exp=1745489532~hmac=dddaaf1d725bfdf28b3aa5a521201418afe582f0ee612ec3ad8cb7026c1143f9&w=826" class="img-fluid rounded" alt="Тварина 2">
    </div>
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/free-photo/green-iguana-closeup-branch-animal-closeup_488145-3329.jpg?t=st=1745485842~exp=1745489442~hmac=83daa778389fd4498a1e5ae9d8d6cc8a2aa04e520b73554f703afffe3b24547f&w=826" class="img-fluid rounded" alt="Тварина 3">
    </div>
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/free-photo/close-up-raccoon-nature_23-2151917112.jpg?t=st=1745485868~exp=1745489468~hmac=fea0462b4e8c3df386e8a5a8906b8cff40f7c1ffa3fe8bdd118f9384282277c1&w=740" class="img-fluid rounded" alt="Тварина 4">
    </div>
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/free-photo/lovely-pet-portrait-isolated_23-2149192352.jpg?t=st=1745486019~exp=1745489619~hmac=528879b981b52127b55282d10101124abc29246f4226306d279161e230d08cda&w=826" class="img-fluid rounded" alt="Тварина 5">
    </div>
    <div class="col-6 col-md-4">
      <img src="https://img.freepik.com/premium-photo/small-dog-flowers-mini-spitz-dog-chocolate-color_753944-4496.jpg?w=740" class="img-fluid rounded" alt="Тварина 6">
    </div>
  </div>
</div>

<!-- Форма зворотного зв'язку -->
<div class="container my-5">
  <h2 class="text-center mb-4">Зв'яжіться з нами</h2>
  <form class="row g-3">
    <div class="col-md-6">
      <label for="name" class="form-label">Ім’я</label>
      <input type="text" class="form-control" id="name" placeholder="Ваше ім’я">
    </div>
    <div class="col-md-6">
      <label for="email" class="form-label">Email</label>
      <input type="email" class="form-control" id="email" placeholder="example@email.com">
    </div>
    <div class="col-12">
      <label for="message" class="form-label">Повідомлення</label>
      <textarea class="form-control" id="message" rows="4" placeholder="Ваше повідомлення..."></textarea>
    </div>
    <div class="col-12 text-center">
      <button type="submit" class="btn btn-success btn-lg">Надіслати</button>
    </div>
  </form>
</div>


<div class="container my-5">
  <h2 class="text-center mb-4">Що кажуть наші відвідувачі</h2>
  <div class="row text-center">
    <div class="col-md-4">
      <div class="card h-100 shadow">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>Це найкращий сайт про тварин, який я коли-небудь бачив!</p>
            <footer class="blockquote-footer mt-2">Іван Петров</footer>
          </blockquote>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card h-100 shadow">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>Мої діти в захваті! Щодня читаємо нові історії.</p>
            <footer class="blockquote-footer mt-2">Олена Коваль</footer>
          </blockquote>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card h-100 shadow">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>Дякую за вашу любов до тварин і таку важливу місію!</p>
            <footer class="blockquote-footer mt-2">Максим Бондар</footer>
          </blockquote>
        </div>
      </div>
    </div>
  </div>
</div>


<div class="container my-5">
  <h2 class="text-center mb-4">Часті запитання</h2>
  <div class="accordion" id="faqAccordion">
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingOne">
        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
          Як можна допомогти тваринам?
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
        <div class="accordion-body">
          Ви можете підтримати притулки, взяти тваринку додому або поширити інформацію!
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingTwo">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo">
          Чи можна надсилати свої історії?
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body">
          Так! Ми з радістю публікуємо ваші історії про улюбленців. Надсилайте через форму на сайті.
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingThree">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree">
          Як часто оновлюється контент?
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
        <div class="accordion-body">
          Ми додаємо новий контент щотижня — стеж за оновленнями!
        </div>
      </div>
    </div>
  </div>
</div>


  <!-- Підвал -->
  <footer class="bg-success text-white text-center py-3">
    <p class="mb-0">&copy; 2025 Світ Тварин. Усі права захищено.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
