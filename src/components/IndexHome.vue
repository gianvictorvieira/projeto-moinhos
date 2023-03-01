<template>
    <html lang="pt-BR">

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta name="description" content="">
        <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
        <meta name="generator" content="Hugo 0.108.0">
        <title>Sidebars · Bootstrap v5.3</title>

        <link rel="canonical" href="https://getbootstrap.com/docs/5.3/examples/sidebars/">





        <link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet">


        <!-- Custom styles for this template -->
        <link href="sidebars.css" rel="stylesheet">
    </head>

    <body>

        <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
            <symbol id="grid" viewBox="0 0 16 16">
                <path
                    d="M1 2.5A1.5 1.5 0 0 1 2.5 1h3A1.5 1.5 0 0 1 7 2.5v3A1.5 1.5 0 0 1 5.5 7h-3A1.5 1.5 0 0 1 1 5.5v-3zM2.5 2a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zm6.5.5A1.5 1.5 0 0 1 10.5 1h3A1.5 1.5 0 0 1 15 2.5v3A1.5 1.5 0 0 1 13.5 7h-3A1.5 1.5 0 0 1 9 5.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zM1 10.5A1.5 1.5 0 0 1 2.5 9h3A1.5 1.5 0 0 1 7 10.5v3A1.5 1.5 0 0 1 5.5 15h-3A1.5 1.5 0 0 1 1 13.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zm6.5.5A1.5 1.5 0 0 1 10.5 9h3a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 13.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3z" />
            </symbol>
        </svg>
        <div class="row">
            <main class="d-flex flex-nowrap col-3">
                <div class="b-example-divider b-example-vr"></div>

                <div class="coluna d-flex flex-column flex-shrink-0 p-3 bg-light" style="width: 280px;">
                    <div class="row">
                        <a href="/"
                            class="col-1 d-flex align-items-center mb-2 m mb-md-3 me-md-auto link-dark text-decoration-none">
                            <img src="../assets/img/favicom-vieira.png" alt="">
                        </a>
                        <a href="/"
                            class="col-6 d-flex align-items-center mb-md-0 me-md-auto link-dark text-decoration-none">
                            <img src="../assets/img/vieira.png" alt="">
                        </a>
                    </div>
                    <hr>
                    <ul class="nav nav-pills flex-column mb-auto">
                        <li class="nav-item">
                            <a href="#" class="nav-link link-dark" aria-current="page">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Home
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link active">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Clientes
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link link-dark">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Moinhos
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link link-dark">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Entregas
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link link-dark">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Peças
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link link-dark">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Peneiras e Martelos
                            </a>
                        </li>
                        <li>
                            <a href="#" class="nav-link link-dark">
                                <svg class="bi pe-none me-2" width="16" height="16">
                                    <use xlink:href="#grid" />
                                </svg>
                                Customizar Menu
                            </a>
                        </li>
                    </ul>
                    <hr>
                    <div class="dropdown">
                        <a href="#" class="d-flex align-items-center link-dark text-decoration-none dropdown-toggle"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            <img src="https://imgur.com/hLHHFnk.png" alt="" width="32" height="32"
                                class="rounded-circle me-2">
                            <strong>Gian Vieira</strong>
                        </a>
                        <ul class="dropdown-menu text-small shadow">
                            <li><a class="dropdown-item" href="#">Configuração</a></li>
                            <li><a class="dropdown-item" href="#">Perfil</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Sair</a></li>
                        </ul>
                    </div>
                </div>

            </main>
            <div class="painel d-flex flex-nowrap col-9 ">
                <div class=" pagina-cliente justify-content-center col-11 mt-10">

                    <div class="cliente">
                        <h1>Painel Clientes</h1>
                    </div>
                    <div class="tabela table-responsive ">
                        <table class="  table table-primary bg-dark border border-size-5">
                            <thead>
                                <tr>
                                    <th scope="col-2">Id</th>
                                    <th scope="col-2">Nome</th>
                                    <th scope="col-3">Endereço</th>
                                    <th scope="col-2">Telefone</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="">
                                    <td scope="row">1</td>
                                    <td>José Soares da Silva</td>
                                    <td>Rua Lino Del Fiol, 485 – Vila Paulina Tatuí – SP </td>
                                    <td>(15) 3251-3501</td>
                                </tr>
                                <tr class="">
                                    <td scope="row">2</td>
                                    <td>Antonio da Costa Oliveira</td>
                                    <td>Rua Benedito Moreira, 64 - Jardim América Tatuí - SP</td>
                                    <td>(15) 3251-9875</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>

            </div>
        </div>
    </body>

    </html>
</template>