<template>
   

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-500 to-purple-500 text-white py-16">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">Une oreille attentive quand vous en avez besoin</h1>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Parlez à un écoutant formé et bienveillant, anonymement et en toute confidentialité</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <button class="bg-white text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-blue-50">
                    Parler à un écoutant
                </button>
                <button class="bg-blue-800 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700">
                    Devenir écoutant
                </button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Comment fonctionne notre plateforme</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-user-check text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Inscription simple</h3>
                    <p class="text-gray-600">Créez un compte anonyme en quelques minutes pour commencer à utiliser nos services.</p>
                </div>
                <div class="text-center p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-comments text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Discutez en toute sécurité</h3>
                    <p class="text-gray-600">Échangez avec un écoutant formé par chat, audio ou vidéo selon vos préférences.</p>
                </div>
                <div class="text-center p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-shield-heart text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Environnement sécurisé</h3>
                    <p class="text-gray-600">Vos conversations sont cryptées et confidentielles, avec un respect strict de l'éthique.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Chat Interface Preview -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Interface de discussion sécurisée</h2>
            <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg overflow-hidden">
                <div class="flex">
                    <!-- Sidebar -->
                    <div class="w-1/3 bg-blue-50 border-r border-gray-200">
                        <div class="p-4 border-b border-gray-200">
                            <h3 class="font-semibold">Écoutants disponibles</h3>
                        </div>
                        <div class="p-4 hover:bg-blue-100 cursor-pointer border-b border-gray-100">
                            <div class="flex items-center">
                                <div class="w-3 h-3 bg-green-500 rounded-full mr-2"></div>
                                <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                    <i class="fas fa-user text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Marie</p>
                                    <p class="text-xs text-gray-500">Disponible</p>
                                </div>
                            </div>
                        </div>
                        <div class="p-4 hover:bg-blue-100 cursor-pointer border-b border-gray-100">
                            <div class="flex items-center">
                                <div class="w-3 h-3 bg-green-500 rounded-full mr-2"></div>
                                <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                    <i class="fas fa-user text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Thomas</p>
                                    <p class="text-xs text-gray-500">Disponible</p>
                                </div>
                            </div>
                        </div>
                        <div class="p-4 hover:bg-blue-100 cursor-pointer">
                            <div class="flex items-center">
                                <div class="w-3 h-3 bg-gray-400 rounded-full mr-2"></div>
                                <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                    <i class="fas fa-user text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Sophie</p>
                                    <p class="text-xs text-gray-500">En conversation</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Chat Area -->
                    <div class="w-2/3 flex flex-col">
                        <div class="p-4 border-b border-gray-200 flex items-center">
                            <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                <i class="fas fa-user text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium">Marie</p>
                                <p class="text-xs text-gray-500">Écoutante • En ligne</p>
                            </div>
                            <div class="ml-auto flex space-x-2">
                                <button class="w-8 h-8 rounded-full hover:bg-gray-100 flex items-center justify-center">
                                    <i class="fas fa-phone text-gray-600"></i>
                                </button>
                                <button class="w-8 h-8 rounded-full hover:bg-gray-100 flex items-center justify-center">
                                    <i class="fas fa-video text-gray-600"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="flex-1 p-4 overflow-y-auto bg-gray-50">
                            <div class="flex mb-4">
                                <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                    <i class="fas fa-user text-blue-600"></i>
                                </div>
                                <div class="bg-white rounded-lg p-3 shadow max-w-xs">
                                    <p>Bonjour, je suis Marie. Je suis là pour vous écouter. Comment allez-vous aujourd'hui ?</p>
                                    <span class="text-xs text-gray-500 mt-1 block">10:05</span>
                                </div>
                            </div>
                            
                            <div class="flex mb-4 justify-end">
                                <div class="bg-blue-100 rounded-lg p-3 shadow max-w-xs">
                                    <p>Bonjour Marie, merci de me répondre. Je ne me sens pas très bien ces derniers temps.</p>
                                    <span class="text-xs text-gray-500 mt-1 block">10:06</span>
                                </div>
                                <div class="w-10 h-10 bg-gray-300 rounded-full flex items-center justify-center ml-3">
                                    <i class="fas fa-user text-gray-600"></i>
                                </div>
                            </div>
                            
                            <div class="flex mb-4">
                                <div class="w-10 h-10 bg-blue-200 rounded-full flex items-center justify-center mr-3">
                                    <i class="fas fa-user text-blue-600"></i>
                                </div>
                                <div class="bg-white rounded-lg p-3 shadow max-w-xs">
                                    <p>Je comprends. Prenez votre temps pour m'expliquer ce qui ne va pas. Je vous écoute.</p>
                                    <span class="text-xs text-gray-500 mt-1 block">10:07</span>
                                </div>
                            </div>
                        </div>
                        
                        <div class="p-4 border-t border-gray-200">
                            <div class="flex">
                                <input type="text" placeholder="Tapez votre message..." class="flex-1 border border-gray-300 rounded-l-lg py-2 px-4 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                                <button class="bg-blue-600 text-white px-4 rounded-r-lg hover:bg-blue-700">
                                    <i class="fas fa-paper-plane"></i>
                                </button>
                            </div>
                            <div class="mt-2 text-xs text-gray-500">
                                <p><i class="fas fa-shield-alt mr-1"></i> Conversation sécurisée et confidentielle</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Emergency Section -->
    <section class="py-16 bg-red-50">
        <div class="container mx-auto px-4 text-center">
            <div class="max-w-2xl mx-auto">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-exclamation-triangle text-red-600 text-2xl"></i>
                    </div>
                    <h2 class="text-2xl font-bold mb-4">Besoin d'aide urgente ?</h2>
                    <p class="text-gray-600 mb-4">Si vous êtes en situation de crise ou avez des pensées suicidaires, contactez immédiatement un service d'urgence :</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
                        <a href="tel:3114" class="bg-red-600 text-white py-3 px-4 rounded-lg font-semibold hover:bg-red-700 flex items-center justify-center">
                            <i class="fas fa-phone mr-2"></i> 3114 (Suicide)
                        </a>
                        <a href="tel:15" class="bg-red-600 text-white py-3 px-4 rounded-lg font-semibold hover:bg-red-700 flex items-center justify-center">
                            <i class="fas fa-ambulance mr-2"></i> 15 (SAMU)
                        </a>
                    </div>
                    <p class="text-sm text-gray-500">Notre plateforme ne remplace pas une assistance médicale professionnelle en cas d'urgence.</p>
                </div>
            </div>
        </div>
    </section>


</template>

<script setup>
    definePageMeta({
        title:'Hello',
    })
</script>