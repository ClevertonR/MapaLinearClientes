
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CLIENTES LINEAR</title>
    <style>
        #map {
            height: 600px;
            width: 100%;
        }
		h1 {
		text-align: center;
		
		body {
		background-color:#8B0000;
		}
		
		
		
    </style>
</head>
<body>
    <h1>ONDE ESTÂO TODOS OS NOSSOS CLIENTES LINEAR SISTEMAS</h1>
    <div id="map"></div>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCEYVrBdLuoKFDsaRKFY0rmVZyphdqfGV0&callback=initMap" async defer></script>
    <script>
        function initMap() {
    const camargos = { lat: -19.917299, lng: -44.083365 };
    const juatuba = { lat: -19.9511, lng: -44.3459 };
    const paraDeMinas = { lat: -19.8605, lng: -44.6083 };
    const mateusLeme = { lat: -19.9869, lng: -44.4319 };
    const saoPaulo = { lat: -23.5505, lng: -46.6333 };
    const aguaBoa = { lat: -17.9914, lng: -42.3804 };
    const aguasLindasDeGoias = { lat: -15.7617, lng: -48.2816 };
    const aimores = { lat: -19.495, lng: -41.0636 };
    const alagoinhas = { lat: -12.1357, lng: -38.4192 };
    const alcobaca = { lat: -17.5195, lng: -39.1986 };
    const alemParaiba = { lat: -21.8733, lng: -42.7042 };
    const almenara = { lat: -16.1835, lng: -40.6942 };
    const alterosa = { lat: -21.248, lng: -46.1383 };
    const altoJequitiba = { lat: -20.4208, lng: -41.9678 };
    const alvinopolis = { lat: -20.1097, lng: -43.0533 };
    const andrelandia = { lat: -21.7411, lng: -44.3111 };
    const angelandia = { lat: -17.7278, lng: -42.2644 };
    const antonioDias = { lat: -19.6497, lng: -42.8736 };
    const aparecidaDeGoiania = { lat: -16.8198, lng: -49.2452 };
    const aracruz = { lat: -19.819, lng: -40.2769 };
    const aracUai = { lat: -16.8523, lng: -42.0709 };
    const araraquara = { lat: -21.7944, lng: -48.1756 };
    const areado = { lat: -21.3575, lng: -46.1428 };
    const aricanduva = { lat: -17.8661, lng: -42.5539 };
    const armacaoDosBuzios = { lat: -22.7525, lng: -41.8847 };
    const arraialDoCabo = { lat: -22.977, lng: -42.0262 };
    const autazes = { lat: -3.5792, lng: -59.1306 };
    const baependi = { lat: -21.9578, lng: -44.8878 };
    const baldim = { lat: -19.2833, lng: -44.4061 };
    const bambui = { lat: -20.0069, lng: -45.975 };
    const baraoDeCocais = { lat: -19.9386, lng: -43.475 };
    const barbacena = { lat: -21.2256, lng: -43.7739 };
    const barraDeSaoFrancisco = { lat: -18.7547, lng: -40.8964 };
    const barueri = { lat: -23.5635, lng: -46.697 };
    const beloHorizonte = { lat: -19.9167, lng: -43.9345 };
    const beloVale = { lat: -20.4078, lng: -44.0278 };
    const berilo = { lat: -16.9561, lng: -42.4608 };
    const bertioga = { lat: -23.8544, lng: -46.1383 };
    const betim = { lat: -19.9678, lng: -44.1983 };
    const bezerros = { lat: -8.2328, lng: -35.7961 };
    const bhte = { lat: -19.9167, lng: -43.9345 };
    const boaVista = { lat: 2.8197, lng: -60.6733 };
    const bocaiuva = { lat: -17.1133, lng: -43.8108 };
    const bomDespacho = { lat: -19.7386, lng: -45.2528 };
    const bomJardimDeMinas = { lat: -21.9478, lng: -44.1889 };
    const bomJesusDoAmparo = { lat: -19.705, lng: -43.4783 };
    const bonfim = { lat: -20.3308, lng: -44.2361 };
    const bonitoDeMinas = { lat: -15.3233, lng: -44.7542 };
    const bragancaPaulista = { lat: -22.9528, lng: -46.5411 };
    const brasilia = { lat: -15.7801, lng: -47.9292 };
    const brasiliaDeMinas = { lat: -16.2047, lng: -44.4292 };
    const brejetuba = { lat: -20.1397, lng: -41.2958 };
    const brumadinho = { lat: -20.1433, lng: -44.1992 };
    const buenopolis = { lat: -17.8742, lng: -44.1778 };
    const buerarema = { lat: -14.9592, lng: -39.3028 };
    const bujaru = { lat: -1.5172, lng: -48.0389 };
    const buritizeiro = { lat: -17.3511, lng: -44.9611 };
    const cachoeiroDeItapemirim = { lat: -20.8489, lng: -41.1128 };
    const caetanopolis = { lat: -19.2978, lng: -44.4183 };
    const caete = { lat: -19.8828, lng: -43.6708 };
    const cafarnaum = { lat: -11.6917, lng: -41.4683 };
    const camaragibe = { lat: -8.0233, lng: -34.9783 };
    const cambui = { lat: -22.6128, lng: -46.0578 };
    const campinas = { lat: -22.9056, lng: -47.0608 };
    const campoGrande = { lat: -20.4697, lng: -54.6208 };
    const candeias = { lat: -20.7697, lng: -45.2761 };
    const canoas = { lat: -29.9178, lng: -51.1836 };
    const capelinha = { lat: -17.6889, lng: -42.5142 };
    const capitaoEneas = { lat: -16.3261, lng: -43.7083 };
    const carandai = { lat: -20.9561, lng: -43.8111 };
    const carangola = { lat: -20.7342, lng: -42.0311 };
    const caravelas = { lat: -17.7261, lng: -39.2592 };
    const cariacica = { lat: -20.2639, lng: -40.4167 };
    const carlosChagas = { lat: -17.6978, lng: -40.7728 };
    const carmoDoCajuru = { lat: -20.1847, lng: -44.7711 };
    const carmoDoParanaiba = { lat: -19.0008, lng: -46.3167 };
    const carrancas = { lat: -21.4889, lng: -44.6442 };
    const caruaru = { lat: -8.2833, lng: -35.9761 };
    const castelo = { lat: -20.6033, lng: -41.2033 };
    const cataguases = { lat: -21.3928, lng: -42.6961 };
    const catalao = { lat: -18.1658, lng: -47.9442 };
    const catasAltas = { lat: -20.0733, lng: -43.4061 };
    const chapadaGaucha = { lat: -15.3011, lng: -45.6111 };
    const cidadeOcidental = { lat: -16.0761, lng: -47.9258 };
    const claroDosPocoes = { lat: -17.0828, lng: -44.2061 };
    const claudio = { lat: -20.4433, lng: -44.7678 };
	const coari = { lat: -4.085, lng: -63.141 };
    const comercinho = { lat: -16.296, lng: -41.794 };
    const conceicaoDoMatoDentro = { lat: -19.034, lng: -43.422 };
    const conselheiroLafaiete = { lat: -20.660, lng: -43.786 };
    const contagem = { lat: -19.938, lng: -44.052 };
    const coracaoDeJesus = { lat: -16.684, lng: -44.363 };
    const cordisburgo = { lat: -19.122, lng: -44.322 };
    const corinto = { lat: -18.364, lng: -44.454 };
	const coronelFabriciano = { lat: -19.518, lng: -42.628 };
const corumba = { lat: -19.009, lng: -57.653 };
const cotia = { lat: -23.603, lng: -46.919 };
const coutoDeMagalhaesDeMinas = { lat: -18.072, lng: -43.464 };
const crato = { lat: -7.215, lng: -39.410 };
const cristalia = { lat: -16.715, lng: -42.857 };
const cristalina = { lat: -16.767, lng: -47.613 };
const curitiba = { lat: -25.428, lng: -49.273 };
const curvelo = { lat: -18.756, lng: -44.430 };
const descalvado = { lat: -21.903, lng: -47.618 };
const diadema = { lat: -23.681, lng: -46.620 };
const diamantina = { lat: -18.241, lng: -43.603 };
const diogoDeVasconcelos = { lat: -20.487, lng: -43.195 };
const divino = { lat: -20.613, lng: -42.144 };
const divinolandiaDeMinas = { lat: -18.800, lng: -42.609 };
const divinopolis = { lat: -20.145, lng: -44.891 };
const domSilverio = { lat: -20.162, lng: -43.008 };
const domingosMartins = { lat: -20.360, lng: -40.659 };
const donaEusebia = { lat: -21.319, lng: -42.807 };
const doresDoIndaia = { lat: -19.463, lng: -45.592 };
const dourados = { lat: -22.223, lng: -54.812 };
const engenheiroNavarro = { lat: -17.283, lng: -43.947 };
const esmeraldas = { lat: -19.762, lng: -44.306 };
const espinosa = { lat: -14.924, lng: -42.809 };
const euclidesDaCunha = { lat: -10.507, lng: -39.015 };
const feiraDeSantana = { lat: -12.266, lng: -38.966 };
const felicioDosSantos = { lat: -18.077, lng: -43.242 };
const felixlandia = { lat: -18.750, lng: -44.898 };
const florestaAzul = { lat: -14.862, lng: -39.657 };
const florestal = { lat: -19.888, lng: -44.431 };
const florianopolis = { lat: -27.595, lng: -48.548 };
const formiga = { lat: -20.461, lng: -45.426 };
const formosa = { lat: -15.540, lng: -47.334 };
const franciscoDumont = { lat: -17.310, lng: -44.236 };
const franciscoSa = { lat: -16.474, lng: -43.489 };
const funilandia = { lat: -19.257, lng: -44.064 };
const goiania = { lat: -16.686, lng: -49.264 };
const gouveia = { lat: -18.451, lng: -43.742 };
const governadorValadares = { lat: -18.854, lng: -41.955 };
const graoMogol = { lat: -16.566, lng: -42.892 };
const guaraciama = { lat: -17.014, lng: -43.667 };
const guarapari = { lat: -20.673, lng: -40.503 };
const guarulhos = { lat: -23.454, lng: -46.533 };
const hortolandia = { lat: -22.858, lng: -47.214 };
const ibirite = { lat: -20.021, lng: -44.058 };
const ibiuna = { lat: -23.654, lng: -47.223 };
const icaraiDeMinas = { lat: -16.214, lng: -44.903 };
const igarape = { lat: -20.070, lng: -44.299 };
const indaiatuba = { lat: -23.088, lng: -47.211 };
const inhapi = { lat: -9.225, lng: -37.750 };
const inhauma = { lat: -19.489, lng: -44.392 };
const inimutaba = { lat: -18.727, lng: -44.358 };
const ipameri = { lat: -17.721, lng: -48.158 };
const ipatinga = { lat: -19.470, lng: -42.548 };
const irece = { lat: -11.303, lng: -41.855 };
const itabira = { lat: -19.623, lng: -43.231 };
const itabirito = { lat: -20.253, lng: -43.801 };
const itabuna = { lat: -14.787, lng: -39.280 };
const itacarambi = { lat: -15.100, lng: -44.094 };
const itacoatiara = { lat: -3.138, lng: -58.444 };
const itaipe = { lat: -17.402, lng: -41.669 };
const itajai = { lat: -26.910, lng: -48.670 };
const itamaraju = { lat: -17.039, lng: -39.531 };
const itamarandiba = { lat: -17.857, lng: -42.858 };
const itamaratiDeMinas = { lat: -21.417, lng: -42.813 };
const itambe = { lat: -7.414, lng: -35.096 };
const itambeDoMatoDentro = { lat: -19.415, lng: -43.318 };
const itanhem = { lat: -17.164, lng: -40.332 };
const itaobim = { lat: -16.558, lng: -41.501 };
const itapecerica = { lat: -20.472, lng: -45.125 };
const itapevi = { lat: -23.548, lng: -46.932 };
const itapissuma = { lat: -7.775, lng: -34.897 };
const itarantim = { lat: -15.652, lng: -40.065 };
const itatiaiuçu = { lat: -20.198, lng: -44.421 };
const itauna = { lat: -20.075, lng: -44.576 };
const itinga = { lat: -16.613, lng: -41.767 };
const itu = { lat: -23.264, lng: -47.299 };
const iuna = { lat: -20.353, lng: -41.533 };
const juizDeFora = { lat: -21.764, lng: -43.350 };
const lagamar = { lat: -18.175, lng: -46.806 };
const lagoaDaPrata = { lat: -20.023, lng: -45.540 };
const lagoaSanta = { lat: -19.630, lng: -43.891 };
const lajeado = { lat: -29.465, lng: -51.964 };
const lajedao = { lat: -17.605, lng: -40.338 };
const lambari = { lat: -21.974, lng: -45.349 };
const laranjal = { lat: -21.371, lng: -42.473 };
const lassance = { lat: -18.044, lng: -44.574 };
const lemeDoPrado = { lat: -17.080, lng: -42.696 };
const leopoldina = { lat: -21.530, lng: -42.642 };
const limeira = { lat: -22.566, lng: -47.401 };
const limeiraDoOeste = { lat: -19.551, lng: -50.581 };
const linhares = { lat: -19.394, lng: -40.065 };
const lontra = { lat: -15.901, lng: -44.307 };
const lucasDoRioVerde = { lat: -13.058, lng: -55.904 };
const luislandia = { lat: -16.109, lng: -44.588 };
const luminarias = { lat: -21.514, lng: -44.903 };
const luziania = { lat: -16.253, lng: -47.950 };
const maceio = { lat: -9.649, lng: -35.708 };
const mairipora = { lat: -23.318, lng: -46.586 };
const mambai = { lat: -13.228, lng: -46.918 };
const manacapuru = { lat: -3.299, lng: -60.620 };
const manaus = { lat: -3.119, lng: -60.021 };
const manga = { lat: -14.752, lng: -43.939 };
const manicore = { lat: -5.812, lng: -61.297 };
const mantena = { lat: -18.776, lng: -40.987 };
const marataizes = { lat: -21.039, lng: -40.838 };
const maravilhas = { lat: -19.507, lng: -44.677 };
const mariana = { lat: -20.377, lng: -43.416 };
const martinhoCampos = { lat: -19.330, lng: -45.243 };
const martinsSoares = { lat: -20.255, lng: -41.878 };
const mataVerde = { lat: -15.686, lng: -40.736 };
const matiasBarbosa = { lat: -21.869, lng: -43.313 };
const matoVerde = { lat: -15.394, lng: -42.860 };
const matozinhos = { lat: -19.554, lng: -44.086 };
const medina = { lat: -16.224, lng: -41.474 };
const minasNovas = { lat: -17.218, lng: -42.588 };
const mineiros = { lat: -17.569, lng: -52.551 };
const mirai = { lat: -21.191, lng: -42.614 };
const moeda = { lat: -20.339, lng: -44.050 };
const montesClaros = { lat: -16.728, lng: -43.857 };
const mutum = { lat: -19.812, lng: -41.440 };
const natal = { lat: -5.794, lng: -35.211 };


const neropolis = { lat: -16.404, lng: -49.222 };
const ninheira = { lat: -15.314, lng: -41.756 };
const niteroi = { lat: -22.883, lng: -43.103 };
const novaEra = { lat: -19.757, lng: -43.033 };
const novaIguacu = { lat: -22.759, lng: -43.451 };
const novaLima = { lat: -19.985, lng: -43.846 };
const novaModica = { lat: -18.441, lng: -41.498 };
const novaOlindaDoNorte = { lat: -3.893, lng: -59.094 };
const novaPorteirinha = { lat: -15.799, lng: -43.294 };
const novaSerrana = { lat: -19.871, lng: -44.984 };
const novaUniao = { lat: -19.687, lng: -43.583 };
const novoGama = { lat: -16.059, lng: -48.041 };
const osasco = { lat: -23.532, lng: -46.792 };

const ouricuri = { lat: -7.882, lng: -40.081 };
const ouroBranco = { lat: -20.526, lng: -43.696 };
const ouroPreto = { lat: -20.385, lng: -43.503 };
const pacaembu = { lat: -21.562, lng: -51.265 };

const papagaios = { lat: -19.441, lng: -44.746 };
const paraDeminas = { lat: -19.8605, lng: -44.6083 };
const paracatu = { lat: -17.225, lng: -46.874 };

const paracuru = { lat: -3.414, lng: -39.030 };
const paraipaba = { lat: -3.437, lng: -39.147 };
const paranaiba = { lat: -19.674, lng: -51.190 };
const paraopeba = { lat: -19.273, lng: -44.404 };
const parintins = { lat: -2.628, lng: -56.735 };

const patosDeMinas = { lat: -18.578, lng: -46.518 };
const patrocinioDoMuriae = { lat: -21.153, lng: -42.212 };
const paulista = { lat: -7.940, lng: -34.873 };
const pedraAzul = { lat: -16.005, lng: -41.290 };
const pedrasDeMariaDaCruz = { lat: -15.603, lng: -44.392 };
const pedroLeopoldo = { lat: -19.618, lng: -44.038 };
const pescador = { lat: -18.357, lng: -41.600 };
const piata = { lat: -13.146, lng: -41.770 };
const piedadeDeCaratinga = { lat: -19.759, lng: -42.075 };
const pinhais = { lat: -25.442, lng: -49.192 };
const piracema = { lat: -20.508, lng: -44.478 };
const piracicaba = { lat: -22.725, lng: -47.649 };
const pirapetinga = { lat: -21.655, lng: -42.343 };
const pirapora = { lat: -17.339, lng: -44.934 };
const pitangui = { lat: -19.682, lng: -44.890 };
const piuma = { lat: -20.835, lng: -40.726 };
const piumhi = { lat: -20.476, lng: -45.958 };
const planaltina = { lat: -15.452, lng: -47.614 };
const pombos = { lat: -8.142, lng: -35.396 };
const pompeu = { lat: -19.225, lng: -45.006 };
const ponteNova = { lat: -20.411, lng: -42.897 };
const pontoDosVolantes = { lat: -16.747, lng: -41.502 };
const porteirinha = { lat: -15.742, lng: -43.028 };
const portoFeliz = { lat: -23.211, lng: -47.525 };
const pousoAlegre = { lat: -22.230, lng: -45.936 };
const prado = { lat: -17.336, lng: -39.222 };
const presidenteFigueiredo = { lat: -2.029, lng: -60.023 };
const presidenteKubitschek = { lat: -18.619, lng: -43.560 };
const presidentePrudente = { lat: -22.121, lng: -51.393 };
const prudenteDeMorais = { lat: -19.474, lng: -44.159 };
const quartelGeral = { lat: -19.270, lng: -45.556 };

const raposos = { lat: -19.963, lng: -43.805 };
const recife = { lat: -8.047, lng: -34.877 };
const reduto = { lat: -20.240, lng: -41.984 };
const resplendor = { lat: -19.324, lng: -41.256 };
const riachoDeSantana = { lat: -13.605, lng: -42.939 };
const ribeiraoDasNeves = { lat: -19.766, lng: -44.086 };


const ribeiraoPreto = { lat: -21.177, lng: -47.810 };
const ribeiraoVermelho = { lat: -21.187, lng: -45.063 };
const rioClaro = { lat: -22.411, lng: -47.561 };
const rioDeJaneiro = { lat: -22.906, lng: -43.172 };
const rioDoPrado = { lat: -16.605, lng: -40.571 };
const rioPardoDeMinas = { lat: -15.609, lng: -42.540 };
const rioPretoDaEva = { lat: -2.704, lng: -59.685 };
const rioVerde = { lat: -17.792, lng: -50.919 };
const rosarioDaLimeira = { lat: -20.981, lng: -42.511 };


const sabara = { lat: -19.889, lng: -43.807 };
const sabinopolis = { lat: -18.665, lng: -43.075 };
const salinas = { lat: -16.170, lng: -42.290 };
const salvador = { lat: -12.971, lng: -38.501 };
const santaBarbara = { lat: -19.960, lng: -43.410 };
const santaBarbaraDoLeste = { lat: -19.975, lng: -42.145 };
const santaBarbaraDoTugurio = { lat: -21.243, lng: -43.560 };
const santaCruzDeSalinas = { lat: -16.096, lng: -42.152 };
const santaCruzDoCapibaribe = { lat: -7.948, lng: -36.205 };
const santaLuzia = { lat: -19.769, lng: -43.851 };
const santaMariaDeItabira = { lat: -19.443, lng: -43.106 };
const santaMariaDoSuacui = { lat: -18.189, lng: -42.413 };
const santanaDoManhuacu = { lat: -20.103, lng: -41.927 };
const santanaDoRiacho = { lat: -19.166, lng: -43.722 };
const santoHipolito = { lat: -18.296, lng: -44.222 };
const saoBenedito = { lat: -4.047, lng: -40.859 };
const saoBeneditoDoSul = { lat: -8.816, lng: -35.945 };
const saoCaitano = { lat: -8.337, lng: -36.286 };
const saoDomingosDoPrata = { lat: -19.867, lng: -42.968 };
const saoFrancisco = { lat: -15.951, lng: -44.864 };
const saoGeraldoDoBaixio = { lat: -18.913, lng: -41.363 };
const saoGoncaloDoAmarante = { lat: -3.607, lng: -38.968 };
const saoGoncaloDoPara = { lat: -19.982, lng: -44.859 };
const saoGoncaloDoRioAbaixo = { lat: -19.822, lng: -43.366 };
const saoGotardo = { lat: -19.308, lng: -46.048 };
const saoJoaoDaLagoa = { lat: -16.848, lng: -44.350 };
const saoJoaoDaPonte = { lat: -15.927, lng: -44.009 };
const saoJoaoDoManhuacu = { lat: -20.393, lng: -42.152 };
const saoJoaoDoManteninha = { lat: -18.723, lng: -41.162 };
const saoJoaoDoOriente = { lat: -19.338, lng: -42.157 };
const saoJoaoDoPacui = { lat: -16.537, lng: -44.513 };
const saoJoaoDoParaiso = { lat: -15.316, lng: -42.020 };
const saoJoaoEvangelista = { lat: -18.548, lng: -42.765 };
const saoJoaquimDeBicas = { lat: -20.048, lng: -44.273 };
const saoJoseDaLapa = { lat: -19.698, lng: -43.972 };
const saoJoseDaVarginha = { lat: -19.700, lng: -44.556 };
const saoJoseDoJacuri = { lat: -18.281, lng: -42.672 };
const saoLourencoDaMata = { lat: -8.006, lng: -35.019 };
const saoLuis = { lat: -2.530, lng: -44.306 };
const saoMateus = { lat: -18.721, lng: -39.857 };



const saoSebastiaoDoMaranhao = { lat: -18.087, lng: -42.565 };
const saoSebastiaoDoOeste = { lat: -20.275, lng: -45.006 };
const sapiranga = { lat: -29.634, lng: -51.006 };
const sapucaiMirim = { lat: -22.740, lng: -45.738 };
const sarzedo = { lat: -20.035, lng: -44.144 };

const serra = { lat: -20.128, lng: -40.307 };
const seteLagoas = { lat: -19.457, lng: -44.241 };
const silvianopolis = { lat: -22.030, lng: -45.838 };
const simonesia = { lat: -20.477, lng: -42.000 };
const sinop = { lat: -11.861, lng: -55.509 };
const sooretama = { lat: -19.189, lng: -40.097 };
const sorocaba = { lat: -23.501, lng: -47.452 };
const sorriso = { lat: -12.542, lng: -55.721 };
const taiobeiras = { lat: -15.810, lng: -42.225 };
const tefe = { lat: -3.368, lng: -64.719 };
const teixeiraDeFreitas = { lat: -17.539, lng: -39.742 };
const teofiloOtoni = { lat: -17.857, lng: -41.505 };
const timoteo = { lat: -19.581, lng: -42.647 };
const toritama = { lat: -8.006, lng: -36.056 };
const tresCoracoes = { lat: -21.696, lng: -45.253 };
const tresLagoas = { lat: -20.752, lng: -51.678 };
const tresPontas = { lat: -21.366, lng: -45.510 };
const turmalina = { lat: -17.282, lng: -42.728 };
const ubai = { lat: -16.252, lng: -44.778 };
const ubaporanga = { lat: -19.635, lng: -42.105 };
const uberaba = { lat: -19.748, lng: -47.931 };
const uberlandia = { lat: -18.912, lng: -48.275 };
const unai = { lat: -16.359, lng: -46.902 };
const uniaoDosPalmares = { lat: -9.159, lng: -36.022 };

const valparaisoDeGoias = { lat: -16.065, lng: -47.975 };
const vargemAlta = { lat: -20.673, lng: -41.008 };
const varginha = { lat: -21.555, lng: -45.436 };
const varzelandia = { lat: -15.699, lng: -44.027 };
const venancioAires = { lat: -29.614, lng: -52.193 };
const vespasiano = { lat: -19.688, lng: -43.923 };
const viana = { lat: -20.390, lng: -40.493 };
const vicosa = { lat: -20.755, lng: -42.874 };
const vilaVelha = { lat: -20.347, lng: -40.294 };
const virgemDaLapa = { lat: -16.806, lng: -42.343 };
const virginopolis = { lat: -18.816, lng: -42.701 };
const viscondeDoRioBranco = { lat: -21.012, lng: -42.836 };
const vitoria = { lat: -20.315, lng: -40.312 };
const vitoriaDeSantoAntao = { lat: -8.118, lng: -35.292 };

	
	
	

            const map = new google.maps.Map(document.getElementById('map'), {
                zoom: 4,
                center: camargos
            });

            const locations = [camargos,juatuba,paraDeMinas,mateusLeme,saoPaulo,aguaBoa,aguasLindasDeGoias,aimores,alagoinhas,alcobaca,alemParaiba,almenara,alterosa,altoJequitiba,alvinopolis,andrelandia,angelandia,antonioDias,aparecidaDeGoiania,aracruz,aracUai,araraquara,areado,aricanduva,armacaoDosBuzios,arraialDoCabo,autazes,baependi,baldim,bambui,baraoDeCocais,barbacena,barraDeSaoFrancisco,barueri,beloHorizonte,beloVale,berilo,bertioga,betim,bezerros,bhte,boaVista,bocaiuva,bomDespacho,bomJardimDeMinas,bomJesusDoAmparo,bonfim,bonitoDeMinas,bragancaPaulista,brasilia,brasiliaDeMinas,brejetuba,brumadinho,buenopolis,buerarema,bujaru,buritizeiro,cachoeiroDeItapemirim,caetanopolis,caete,cafarnaum,camaragibe,cambui,campinas,campoGrande,candeias,canoas,capelinha,capitaoEneas,carandai,carangola,caravelas,cariacica,carlosChagas,carmoDoCajuru,carmoDoParanaiba,carrancas,caruaru,castelo,cataguases,catalao,catasAltas,chapadaGaucha,cidadeOcidental,claroDosPocoes,claudio,coari,comercinho,conceicaoDoMatoDentro,conselheiroLafaiete,contagem,coracaoDeJesus,cordisburgo,corinto,coronelFabriciano,corumba,cotia,coutoDeMagalhaesDeMinas,crato,cristalia,cristalina,curitiba,curvelo,descalvado,diadema,diamantina,diogoDeVasconcelos,divino,divinolandiaDeMinas,divinopolis,domSilverio,domingosMartins,donaEusebia,doresDoIndaia,dourados,engenheiroNavarro,esmeraldas,espinosa,euclidesDaCunha,feiraDeSantana,felicioDosSantos,felixlandia,florestaAzul,florestal,florianopolis,formiga,formosa,franciscoDumont,franciscoSa,funilandia,goiania,gouveia,governadorValadares,graoMogol,guaraciama,guarapari,guarulhos,hortolandia,ibirite,ibiuna,icaraiDeMinas,igarape,indaiatuba,inhapi,inhauma,inimutaba,ipameri,ipatinga,irece,itabira,itabirito,itabuna,itacarambi,itacoatiara,itaipe,itajai,itamaraju,itamarandiba,itamaratiDeMinas,itambe,itambeDoMatoDentro,itanhem,itaobim,itapecerica,itapevi,itapissuma,itarantim,itatiaiuçu,itauna,itinga,itu,iuna,juizDeFora,lagamar,lagoaDaPrata,lagoaSanta,lajeado,lajedao,lambari,laranjal,lassance,lemeDoPrado,leopoldina,limeira,limeiraDoOeste,linhares,lontra,lucasDoRioVerde,luislandia,luminarias,luziania,maceio,mairipora,mambai,manacapuru,manaus,manga,manicore,mantena,marataizes,maravilhas,mariana,martinhoCampos,martinsSoares,mataVerde,matiasBarbosa,matoVerde,matozinhos,medina,minasNovas,mineiros,mirai,moeda,montesClaros,mutum,natal,neropolis,ninheira,niteroi,novaEra,novaIguacu,novaLima,novaModica,novaOlindaDoNorte,novaPorteirinha,novaSerrana,novaUniao,novoGama,osasco,ouricuri,ouroBranco,ouroPreto,pacaembu,papagaios,paraDeminas,paracatu,paracuru,paraipaba,paranaiba,paraopeba,parintins,patosDeMinas,patrocinioDoMuriae,paulista,pedraAzul,pedrasDeMariaDaCruz,pedroLeopoldo,pescador,piata,piedadeDeCaratinga,pinhais,piracema,piracicaba,pirapetinga,pirapora,pitangui,piuma,piumhi,planaltina,pombos,pompeu,ponteNova,pontoDosVolantes,porteirinha,portoFeliz,pousoAlegre,prado];
            locations.forEach(location => {
                new google.maps.Marker({
                    position: location,
                    map: map
                });
            });

         

            line.setMap(map);
        }
    </script>
</body>
</html>
