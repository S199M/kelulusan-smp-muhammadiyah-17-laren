body {
        font-family: 'Poppins', sans-serif;
        background-color: #f8f9fa;
    }
    
    .title {
        font-family: 'Playfair Display', serif;
    }
    
    .gold-text {
        color: #D4AF37;
    }
    
    .navy-bg {
        background-color: #0A1747;
    }
    
    .gold-bg {
        background-color: #D4AF37;
    }
    
    .certificate {
        background-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43-7c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm63 31c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM34 90c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm56-76c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM12 86c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm28-65c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm23-11c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-6 60c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm29 22c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zM32 63c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm57-13c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-9-21c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM60 91c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM35 41c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM12 60c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2z' fill='%23D4AF37' fill-opacity='0.1' fill-rule='evenodd'/%3E%3C/svg%3E");
    }
    
    .result-card {
        transition: all 0.3s ease;
    }
    
    .result-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 25px -5px rgba(10, 23, 71, 0.1);
    }
    
    .confetti {
        position: absolute;
        width: 10px;
        height: 10px;
        background-color: #D4AF37;
        animation: confetti-fall 3s ease-in-out infinite;
        opacity: 0;
    }
    
    @keyframes confetti-fall {
        0% {
            transform: translateY(-100px) rotate(0deg);
            opacity: 1;
        }
        100% {
            transform: translateY(500px) rotate(360deg);
            opacity: 0;
        }
    }
    
    .search-container {
        position: relative;
    }
    
    .search-results {
        max-height: 300px;
        overflow-y: auto;
    }
    
    .modal {
        transition: opacity 0.3s ease;
    }
</style>
    <!-- Main Content -->
    <main class="flex-grow container mx-auto px-4 py-8">
        <!-- Hero Section -->
        <section class="mb-12 text-center">
            <div class="certificate bg-white rounded-lg shadow-lg p-6 md:p-10 mb-8 relative overflow-hidden">
                <div class="absolute top-0 right-0">
                    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" opacity="0.2">
                        <path d="M12 2L8 6H4v4l-2 4 2 4v4h4l4 2 4-2h4v-4l2-4-2-4V6h-4l-4-4z"></path>
                    </svg>
                </div>
                <div class="absolute bottom-0 left-0">
                    <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 24 24" fill="none" stroke="#0A1747" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" opacity="0.1">
                        <circle cx="12" cy="12" r="10"></circle>
                        <path d="M12 8v8"></path>
                        <path d="M8 12h8"></path>
                    </svg>
                </div>
                
                <h2 class="text-2xl md:text-4xl font-bold title mb-4 navy-bg text-white py-2 rounded-lg">Pengumuman Kelulusan</h2>
                <div class="flex justify-center mb-6 space-x-4">
                    <!-- Graduation Cap Icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#0A1747" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 10v6M2 10l10-5 10 5-10 5z"></path>
                        <path d="M6 12v5c0 2 2 3 6 3s6-1 6-3v-5"></path>
                    </svg>
                    <!-- Firework Icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M12 2v8M12 22v-8M4.93 4.93l5.66 5.66M18.07 18.07l-5.66-5.66M2 12h8M22 12h-8M4.93 19.07l5.66-5.66M18.07 5.93l-5.66 5.66"></path>
                    </svg>
                    <!-- Book Icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#0A1747" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path>
                        <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path>
                    </svg>
                </div>
                <p class="text-lg md:text-xl mb-6">Selamat kepada seluruh siswa yang telah berhasil menyelesaikan pendidikan di SMP MUHAMMADIYAH 17 LAREN. Pencarian hasil kelulusan dapat dilakukan melalui form di bawah ini.</p>
                
                <div class="search-container max-w-md mx-auto">
                    <div class="relative">
                        <input type="text" id="searchInput" placeholder="Cari nama atau NISN..." class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-900">
                        <button id="searchButton" class="absolute right-2 top-2 gold-bg text-white px-4 py-1 rounded-lg hover:bg-yellow-600 transition">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <circle cx="11" cy="11" r="8"></circle>
                                <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                            </svg>
                        </button>
                    </div>
                    <div id="searchResults" class="search-results mt-2 bg-white rounded-lg shadow-lg hidden"></div>
                </div>
            </div>
        </section>

        <!-- Results Section -->
        <section>
            <h3 class="text-xl md:text-2xl font-bold title mb-6 text-center">Daftar Kelulusan</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6" id="resultsContainer">
                <!-- Cards will be generated by JavaScript -->
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="navy-bg text-white py-6">
        <div class="container mx-auto px-4 text-center">
            <p class="mb-2">© 2025 SMP MUHAMMADIYAH 17 LAREN. Hak Cipta Dilindungi.</p>
            <p class="text-sm gold-text">Selamat melanjutkan ke jenjang pendidikan berikutnya!</p>
            <div class="flex justify-center mt-4 space-x-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                    <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                    <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path>
                </svg>
            </div>
        </div>
    </footer>
</div>

<!-- Modal -->
<div id="detailModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden modal">
    <div class="bg-white rounded-lg shadow-xl p-6 md:p-8 w-11/12 max-w-md mx-4 relative">
        <button id="closeModal" class="absolute top-4 right-4 text-gray-500 hover:text-gray-700">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <line x1="18" y1="6" x2="6" y2="18"></line>
                <line x1="6" y1="6" x2="18" y2="18"></line>
            </svg>
        </button>
        <div id="modalContent" class="text-center">
            <!-- Content will be filled by JavaScript -->
        </div>
    </div>
</div>

<script>
    // Student data
    const students = [
        { id: 1, name: "AISY AISYAH SALWA", nisn: "12345678", score: 88, status: "Lulus" },
        { id: 2, name: "ANANDA AFIF FATAHILLAH PAMBUDI", nisn: "", score: 90, status: "Lulus" },
        { id: 3, name: "ANNISA QOTRUN NADA", nisn: "", score: 89, status: "Lulus" },
        { id: 4, name: "AURA AMIROTUN NISA", nisn: "", score: 93, status: "Lulus" },
        { id: 5, name: "APRECIA FIRDAUSI NUZULA", nisn: "", score: 78, status: "Lulus" },
        { id: 6, name: "BILQIS ASSYIFA NURYASIN", nisn: "", score: 77, status: "Lulus" },
        { id: 7, name: "FAHYATUL HIMA ISLAMIYAH", nisn: "", score: 90, status: "Lulus" },
        { id: 8, name: "KANZA O ZAHWA", nisn: "", score: 72, status: "Lulus" },
        { id: 9, name: "M. TSALIS BIRAL FAHLEVI ARDIANSYAH", nisn: "", score: 88, status: "Lulus" },
        { id: 10, name: "MOCH. AFREZI NURDIANTO", nisn: "", score: 87, status: "Lulus" },
        { id: 11, name: "NALIYATUL ILMIYAH", nisn: "", score: 91, status: "Lulus" },
        { id: 12, name: "NAUVA ZAHRA TSABITA", nisn: "", score: 77, status: "Lulus" },
        { id: 13, name: "SALSA PRATIWI", nisn: "", score: 90, status: "Lulus" }
    ];

    // DOM elements
    const resultsContainer = document.getElementById('resultsContainer');
    const searchInput = document.getElementById('searchInput');
    const searchButton = document.getElementById('searchButton');
    const searchResults = document.getElementById('searchResults');
    const detailModal = document.getElementById('detailModal');
    const closeModal = document.getElementById('closeModal');
    const modalContent = document.getElementById('modalContent');

    // Generate student cards
    function generateStudentCards() {
        resultsContainer.innerHTML = '';
        
        students.forEach(student => {
            const card = document.createElement('div');
            card.className = 'result-card bg-white rounded-lg shadow-lg p-6 border-l-4 border-blue-900 hover:border-yellow-500 transition-all';
            card.innerHTML = `
                <h4 class="font-bold text-lg mb-2 truncate">${student.name}</h4>
                <p class="text-gray-600 mb-1">No. ${student.id}</p>
                ${student.nisn ? `<p class="text-gray-600 mb-3">NISN: ${student.nisn}</p>` : '<p class="text-gray-600 mb-3">NISN: -</p>'}
                <div class="flex justify-between items-center">
                    <span class="text-sm text-gray-500">Nilai: ${student.score}</span>
                    <span class="px-3 py-1 rounded-full text-white text-sm font-medium bg-green-600">${student.status}</span>
                </div>
                <button class="view-details mt-4 w-full py-2 navy-bg text-white rounded-lg hover:bg-blue-800 transition" data-id="${student.id}">Lihat Detail</button>
            `;
            resultsContainer.appendChild(card);
        });

        // Add event listeners to view detail buttons
        document.querySelectorAll('.view-details').forEach(button => {
            button.addEventListener('click', () => {
                const studentId = parseInt(button.getAttribute('data-id'));
                showStudentDetail(studentId);
            });
        });
    }

    // Search functionality
    function setupSearch() {
        searchButton.addEventListener('click', performSearch);
        searchInput.addEventListener('keyup', (e) => {
            if (e.key === 'Enter') {
                performSearch();
            }
        });

        searchInput.addEventListener('focus', () => {
            if (searchInput.value.length > 0) {
                performSearch();
            }
        });

        document.addEventListener('click', (e) => {
            if (!searchInput.contains(e.target) && !searchResults.contains(e.target) && !searchButton.contains(e.target)) {
                searchResults.classList.add('hidden');
            }
        });
    }

    function performSearch() {
        const query = searchInput.value.toLowerCase().trim();
        
        if (query.length === 0) {
            searchResults.classList.add('hidden');
            return;
        }

        const filteredStudents = students.filter(student => 
            student.name.toLowerCase().includes(query) || 
            (student.nisn && student.nisn.includes(query))
        );

        displaySearchResults(filteredStudents);
    }

    function displaySearchResults(results) {
        searchResults.innerHTML = '';
        
        if (results.length === 0) {
            searchResults.innerHTML = `
                <div class="p-4 text-center text-gray-500">
                    Tidak ada hasil yang ditemukan
                </div>
            `;
            searchResults.classList.remove('hidden');
            return;
        }

        results.forEach(student => {
            const resultItem = document.createElement('div');
            resultItem.className = 'p-3 border-b hover:bg-gray-100 cursor-pointer';
            resultItem.innerHTML = `
                <div class="font-medium">${student.name}</div>
                <div class="text-sm text-gray-600">${student.nisn ? `NISN: ${student.nisn}` : 'NISN: -'}</div>
            `;
            resultItem.addEventListener('click', () => {
                showStudentDetail(student.id);
                searchResults.classList.add('hidden');
            });
            searchResults.appendChild(resultItem);
        });

        searchResults.classList.remove('hidden');
    }

    // Show student detail in modal
    function showStudentDetail(studentId) {
        const student = students.find(s => s.id === studentId);
        
        if (!student) return;

        modalContent.innerHTML = `
            <div class="mb-6">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" width="64" height="64" fill="#0A1747" class="mx-auto mb-4">
                    <path d="M32 2L4 18v4h56v-4L32 2zm0 4.9l20.7 11.8H11.3L32 6.9zM8 26v26h4V26H8zm44 0v26h4V26h-4zM16 56h32v6H16v-6zm32-4V26H16v26h32zm-24-20h16v4H24v-4zm0 8h16v4H24v-4zm0 8h16v4H24v-4z"/>
                </svg>
                <h3 class="text-2xl font-bold title navy-bg text-white py-2 rounded-lg mb-4">Detail Kelulusan</h3>
            </div>
            <div class="mb-6 text-left">
                <div class="mb-3">
                    <span class="font-medium text-gray-600">Nama:</span>
                    <p class="font-bold text-lg">${student.name}</p>
                </div>
                <div class="mb-3">
                    <span class="font-medium text-gray-600">Nomor Peserta:</span>
                    <p>${student.id}</p>
                </div>
                <div class="mb-3">
                    <span class="font-medium text-gray-600">NISN:</span>
                    <p>${student.nisn || '-'}</p>
                </div>
                <div class="mb-3">
                    <span class="font-medium text-gray-600">Nilai Akhir:</span>
                    <p>${student.score}</p>
                </div>
                <div class="mb-6">
                    <span class="font-medium text-gray-600">Status:</span>
                    <p class="inline-block px-3 py-1 rounded-full text-white text-sm font-medium bg-green-600 mt-1">${student.status}</p>
                </div>
            </div>
            <div class="certificate p-4 rounded-lg border border-gray-200 mb-6">
                <h4 class="font-bold text-lg mb-2 gold-text">Selamat!</h4>
                <p>Anda telah berhasil menyelesaikan pendidikan di SMP MUHAMMADIYAH 17 LAREN dengan baik. Semoga sukses di jenjang pendidikan selanjutnya!</p>
            </div>
            <button id="printResult" class="gold-bg text-white px-6 py-2 rounded-lg hover:bg-yellow-600 transition flex items-center justify-center mx-auto">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2">
                    <polyline points="6 9 6 2 18 2 18 9"></polyline>
                    <path d="M6 18H4a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2"></path>
                    <rect x="6" y="14" width="12" height="8"></rect>
                </svg>
                Cetak Hasil
            </button>
        `;

        // Add confetti effect for passed students
        if (student.status === "Lulus") {
            createConfetti();
        }

        // Add print functionality
        document.getElementById('printResult').addEventListener('click', () => {
            window.print();
        });

        detailModal.classList.remove('hidden');
    }

    // Close modal
    function setupModal() {
        closeModal.addEventListener('click', () => {
            detailModal.classList.add('hidden');
        });

        window.addEventListener('click', (e) => {
            if (e.target === detailModal) {
                detailModal.classList.add('hidden');
            }
        });
    }

    // Create confetti effect
    function createConfetti() {
        const modalRect = modalContent.getBoundingClientRect();
        const confettiCount = 50;
        
        for (let i = 0; i < confettiCount; i++) {
            const confetti = document.createElement('div');
            confetti.className = 'confetti';
            confetti.style.left = `${Math.random() * modalRect.width}px`;
            confetti.style.top = `${-10}px`;
            confetti.style.backgroundColor = i % 2 === 0 ? '#D4AF37' : '#0A1747';
            confetti.style.animationDelay = `${Math.random() * 3}s`;
            modalContent.appendChild(confetti);
            
            // Remove confetti after animation
            setTimeout(() => {
                confetti.remove();
            }, 3000);
        }
    }

    // Initialize
    document.addEventListener('DOMContentLoaded', () => {
        generateStudentCards();
        setupSearch();
        setupModal();
    });
</script>
