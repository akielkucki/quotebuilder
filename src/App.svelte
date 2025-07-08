<script>

</script>

<main class="min-h-screen bg-gradient-to-br from-gray-900 via-gray-800 to-emerald-900">
  <div class="container mx-auto px-4 py-8 max-w-7xl">

    <!-- Header -->
    <div class="text-center mb-12 animate-fade-in">
      <h1 class="text-5xl font-bold bg-gradient-to-r from-emerald-400 to-green-300 bg-clip-text text-transparent mb-4">
        Quote Builder
      </h1>
      <p class="text-gray-300 text-lg">Create professional quotes with ease</p>
      <div class="mt-6 flex justify-center space-x-8 text-sm">
        <div class="bg-gray-800/50 backdrop-blur-sm rounded-full px-4 py-2 border border-emerald-500/20">
          <span class="text-gray-400">Total Quotes: </span>
          <span class="font-semibold text-emerald-400">0</span>
        </div>
        <div class="bg-gray-800/50 backdrop-blur-sm rounded-full px-4 py-2 border border-emerald-500/20">
          <span class="text-gray-400">Revenue: </span>
          <span class="font-semibold text-green-400">$0.00</span>
        </div>
      </div>
    </div>

    <div class="grid lg:grid-cols-4 gap-8">

      <!-- Quote Form -->
      <div class="lg:col-span-2 space-y-6">

        <!-- Client Information -->
        <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
          <h2 class="text-xl font-semibold text-gray-100 mb-6 flex items-center">
            <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
            Client Information
          </h2>
          <div class="grid md:grid-cols-2 gap-4">
            <div class="space-y-2">
              <label class="block text-sm font-medium text-gray-300">Client Name</label>
              <input
                      type="text"
                      class="w-full px-4 py-3 bg-gray-700/50 border border-gray-600 rounded-xl text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300 hover:border-emerald-500/50"
                      placeholder="Enter client name"
              />
            </div>
            <div class="space-y-2">
              <label class="block text-sm font-medium text-gray-300">Company</label>
              <input
                      type="text"
                      class="w-full px-4 py-3 bg-gray-700/50 border border-gray-600 rounded-xl text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300 hover:border-emerald-500/50"
                      placeholder="Company name"
              />
            </div>
            <div class="space-y-2">
              <label class="block text-sm font-medium text-gray-300">Email</label>
              <input
                      type="email"
                      class="w-full px-4 py-3 bg-gray-700/50 border border-gray-600 rounded-xl text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300 hover:border-emerald-500/50"
                      placeholder="client@email.com"
              />
            </div>
            <div class="space-y-2">
              <label class="block text-sm font-medium text-gray-300">Phone</label>
              <input
                      type="tel"
                      class="w-full px-4 py-3 bg-gray-700/50 border border-gray-600 rounded-xl text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300 hover:border-emerald-500/50"
                      placeholder="(555) 123-4567"
              />
            </div>
          </div>
        </div>

        <!-- Quote Items -->
        <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
          <div class="flex justify-between items-center mb-6">
            <h2 class="text-xl font-semibold text-gray-100 flex items-center">
              <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
              Quote Items
            </h2>
            <button class="bg-gradient-to-r from-emerald-600 to-green-600 hover:from-emerald-500 hover:to-green-500 text-white px-6 py-2 rounded-xl font-medium transition-all duration-300 shadow-lg hover:shadow-emerald-500/25 transform hover:scale-105">
              <svg class="w-4 h-4 inline mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path>
              </svg>
              Add Item
            </button>
          </div>

          <!-- Sample Item Row -->
          <div class="bg-gray-700/30 p-4 rounded-xl border border-gray-600/50 hover:border-emerald-500/50 transition-all duration-300 mb-4">
            <div class="grid md:grid-cols-12 gap-3 items-end">
              <div class="md:col-span-5 space-y-2">
                <label class="block text-sm font-medium text-gray-300">Description</label>
                <input
                        type="text"
                        class="w-full px-3 py-2 bg-gray-800/50 border border-gray-600 rounded-lg text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                        placeholder="Service description"
                />
              </div>
              <div class="md:col-span-2 space-y-2">
                <label class="block text-sm font-medium text-gray-300">Quantity</label>
                <input
                        type="number"
                        class="w-full px-3 py-2 bg-gray-800/50 border border-gray-600 rounded-lg text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                        placeholder="1"
                />
              </div>
              <div class="md:col-span-2 space-y-2">
                <label class="block text-sm font-medium text-gray-300">Rate ($)</label>
                <input
                        type="number"
                        class="w-full px-3 py-2 bg-gray-800/50 border border-gray-600 rounded-lg text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                        placeholder="0.00"
                />
              </div>
              <div class="md:col-span-2 space-y-2">
                <label class="block text-sm font-medium text-gray-300">Total</label>
                <div class="px-3 py-2 bg-gray-800/70 border border-gray-600 rounded-lg font-medium text-emerald-400">
                  $0.00
                </div>
              </div>
              <div class="md:col-span-1">
                <button class="w-full bg-red-600/80 hover:bg-red-600 text-white p-2 rounded-lg transition-all duration-300 hover:shadow-lg">
                  <svg class="w-4 h-4 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"></path>
                  </svg>
                </button>
              </div>
            </div>
          </div>

          <!-- Quote Settings -->
          <div class="mt-6 pt-6 border-t border-gray-600/50">
            <div class="grid md:grid-cols-3 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-medium text-gray-300">Tax Rate (%)</label>
                <input
                        type="number"
                        class="w-full px-3 py-2 bg-gray-700/50 border border-gray-600 rounded-lg text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                        placeholder="8.5"
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-medium text-gray-300">Discount ($)</label>
                <input
                        type="number"
                        class="w-full px-3 py-2 bg-gray-700/50 border border-gray-600 rounded-lg text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                        placeholder="0.00"
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-medium text-gray-300">Valid Until</label>
                <input
                        type="date"
                        class="w-full px-3 py-2 bg-gray-700/50 border border-gray-600 rounded-lg text-gray-100 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- Notes Section -->
        <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
          <h2 class="text-xl font-semibold text-gray-100 mb-4 flex items-center">
            <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
            Additional Notes
          </h2>
          <textarea
                  rows="4"
                  class="w-full px-4 py-3 bg-gray-700/50 border border-gray-600 rounded-xl text-gray-100 placeholder-gray-400 focus:ring-2 focus:ring-emerald-500 focus:border-transparent transition-all duration-300 resize-none hover:border-emerald-500/50"
                  placeholder="Add any additional terms, conditions, or notes..."
          ></textarea>
        </div>
      </div>

      <!-- Quote Preview -->
      <div class="lg:col-span-1">
        <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 sticky top-8 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
          <h2 class="text-xl font-semibold text-gray-100 mb-6 flex items-center">
            <div class="w-2 h-2 bg-green-400 rounded-full mr-3 animate-pulse"></div>
            Quote Summary
          </h2>

          <div class="space-y-4">
            <div class="flex justify-between items-center py-3 border-b border-gray-600/50">
              <span class="text-gray-300">Subtotal:</span>
              <span class="font-semibold text-gray-100">$0.00</span>
            </div>
            <div class="flex justify-between items-center py-3 border-b border-gray-600/50">
              <span class="text-gray-300">Discount:</span>
              <span class="font-semibold text-red-400">-$0.00</span>
            </div>
            <div class="flex justify-between items-center py-3 border-b border-gray-600/50">
              <span class="text-gray-300">Tax:</span>
              <span class="font-semibold text-gray-100">$0.00</span>
            </div>
            <div class="flex justify-between items-center py-4 border-t-2 border-emerald-500/50">
              <span class="text-lg font-semibold text-gray-100">Total:</span>
              <span class="text-2xl font-bold bg-gradient-to-r from-emerald-400 to-green-400 bg-clip-text text-transparent">$0.00</span>
            </div>
          </div>

          <div class="mt-8 space-y-3">
            <button class="w-full bg-gradient-to-r from-emerald-600 to-green-600 hover:from-emerald-500 hover:to-green-500 text-white py-3 px-4 rounded-xl font-semibold transition-all duration-300 shadow-lg hover:shadow-emerald-500/25 transform hover:scale-105">
              <svg class="w-5 h-5 inline mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-3m-1 4l-3 3m0 0l-3-3m3 3V4"></path>
              </svg>
              Save Quote
            </button>
            <button class="w-full bg-gray-700/50 hover:bg-gray-600/50 text-gray-100 py-3 px-4 rounded-xl font-semibold transition-all duration-300 border border-gray-600 hover:border-gray-500">
              <svg class="w-5 h-5 inline mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"></path>
              </svg>
              New Quote
            </button>
          </div>
        </div>
      </div>

      <!-- Analytics Panel -->
      <div class="lg:col-span-1">
        <div class="space-y-6">

          <!-- Revenue Chart -->
          <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
            <h3 class="text-lg font-semibold text-gray-100 mb-4 flex items-center">
              <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
              Revenue Trends
            </h3>
            <div class="relative h-64 bg-gray-700/20 rounded-xl flex items-center justify-center">
              <div class="text-gray-400">Chart will appear here</div>
            </div>
          </div>

          <!-- Quote Status -->
          <div class="bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
            <h3 class="text-lg font-semibold text-gray-100 mb-4 flex items-center">
              <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
              Quote Status
            </h3>
            <div class="space-y-3">
              <div class="flex items-center justify-between">
                <div class="flex items-center">
                  <div class="w-3 h-3 bg-green-400 rounded-full mr-2"></div>
                  <span class="text-gray-300">Accepted</span>
                </div>
                <span class="text-green-400 font-semibold">0</span>
              </div>
              <div class="flex items-center justify-between">
                <div class="flex items-center">
                  <div class="w-3 h-3 bg-yellow-400 rounded-full mr-2"></div>
                  <span class="text-gray-300">Pending</span>
                </div>
                <span class="text-yellow-400 font-semibold">0</span>
              </div>
              <div class="flex items-center justify-between">
                <div class="flex items-center">
                  <div class="w-3 h-3 bg-red-400 rounded-full mr-2"></div>
                  <span class="text-gray-300">Rejected</span>
                </div>
                <span class="text-red-400 font-semibold">0</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Saved Quotes Table -->
    <div class="mt-12 bg-gray-800/40 backdrop-blur-sm rounded-2xl border border-emerald-500/20 p-6 hover:border-emerald-500/40 transition-all duration-500 animate-slide-up">
      <h2 class="text-xl font-semibold text-gray-100 mb-6 flex items-center">
        <div class="w-2 h-2 bg-emerald-400 rounded-full mr-3 animate-pulse"></div>
        Saved Quotes
      </h2>

      <div class="overflow-x-auto">
        <table class="w-full">
          <thead>
          <tr class="border-b border-gray-600/50">
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Quote #</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Client</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Company</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Date</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Total</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Status</th>
            <th class="text-left py-4 px-4 font-semibold text-gray-300">Actions</th>
          </tr>
          </thead>
          <tbody>
          <tr class="border-b border-gray-600/30 hover:bg-gray-700/20 transition-colors duration-300">
            <td class="py-4 px-4 font-medium text-gray-100">#001</td>
            <td class="py-4 px-4 text-gray-300">John Doe</td>
            <td class="py-4 px-4 text-gray-300">Tech Corp</td>
            <td class="py-4 px-4 text-gray-300">2024-01-15</td>
            <td class="py-4 px-4 font-semibold text-emerald-400">$5,425.00</td>
            <td class="py-4 px-4">
                <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-green-900/50 text-green-400 border border-green-500/30">
                  Accepted
                </span>
            </td>
            <td class="py-4 px-4">
              <div class="flex space-x-2">
                <button class="text-emerald-400 hover:text-emerald-300 transition-colors duration-200">
                  <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path>
                  </svg>
                </button>
                <button class="text-red-400 hover:text-red-300 transition-colors duration-200">
                  <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"></path>
                  </svg>
                </button>
              </div>
            </td>
          </tr>
          <tr class="text-center">
            <td colspan="7" class="py-12 px-4 text-gray-500">
              <div class="flex flex-col items-center">
                <svg class="w-12 h-12 text-gray-600 mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                </svg>
                <p class="text-lg">No quotes saved yet</p>
                <p class="text-sm text-gray-600">Create your first quote to get started</p>
              </div>
            </td>
          </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</main>

<style>
  @keyframes fade-in {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes slide-up {
    from {
      opacity: 0;
      transform: translateY(40px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .animate-fade-in {
    animation: fade-in 0.8s ease-out;
  }

  .animate-slide-up {
    animation: slide-up 0.6s ease-out;
  }

  /* Smooth scrolling */
  html {
    scroll-behavior: smooth;
  }

  /* Custom scrollbar */
  ::-webkit-scrollbar {
    width: 8px;
  }

  ::-webkit-scrollbar-track {
    background: #374151;
  }

  ::-webkit-scrollbar-thumb {
    background: #10b981;
    border-radius: 4px;
  }

  ::-webkit-scrollbar-thumb:hover {
    background: #059669;
  }
</style>