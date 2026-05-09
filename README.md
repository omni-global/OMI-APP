// file: app/page.js
import React from 'react';

export default function GlobalSuperApp() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900 font-sans">
      {/* 10. Password Locking System & 8. Login */}
      <nav className="p-4 bg-blue-600 text-white flex justify-between items-center shadow-lg">
        <h1 className="text-xl font-bold">Omni-Global Super App</h1>
        <div className="flex gap-4">
          <span className="bg-blue-700 px-3 py-1 rounded">Language: Global (9)</span>
          <button className="bg-red-500 px-4 py-1 rounded font-bold">SOS (6)</button>
        </div>
      </nav>

      <main className="p-6 grid grid-cols-1 md:grid-cols-3 gap-6">
        
        {/* Section 1: Security & Health (4, 5, 6) */}
        <div className="bg-white p-6 rounded-xl shadow-md border-t-4 border-red-500">
          <h2 className="text-lg font-bold mb-4">Safety & Well-being</h2>
          <button className="w-full mb-3 bg-red-100 text-red-700 p-3 rounded">Live Location Tracker (6)</button>
          <div className="text-sm text-gray-600 italic">"Mental Peace Tip: Breathe and focus on the now." (5)</div>
          <div className="mt-4 p-3 bg-green-50 rounded">Health Care: Daily Routine (4)</div>
        </div>

        {/* Section 2: Finance & Investment (3, 11, 12, 13) */}
        <div className="bg-white p-6 rounded-xl shadow-md border-t-4 border-yellow-500">
          <h2 className="text-lg font-bold mb-4">Global Finance Hub</h2>
          <div className="p-3 bg-red-50 text-red-600 font-bold mb-2 text-center">Alert: Market Fall Alert (11)</div>
          <ul className="space-y-2 text-sm">
            <li>💰 Investment Tips: Gold, Mutual Funds (3)</li>
            <li>📈 Earning Planning: 10-Year Growth (13)</li>
            <li>📉 Income Saving: Optimize Expenses (12)</li>
          </ul>
          <button className="w-full mt-4 bg-yellow-500 text-white p-2 rounded">Investment Calculator</button>
        </div>

        {/* Section 3: Info, Stats & Mail (1, 2, 7) */}
        <div className="bg-white p-6 rounded-xl shadow-md border-t-4 border-blue-500">
          <h2 className="text-lg font-bold mb-4">World Info & News</h2>
          <div className="space-y-3">
            <div className="p-2 border-b">Global Business News (2)</div>
            <div className="p-2 border-b">Worldwide Statistics (1)</div>
            <div className="p-2 bg-gray-100 rounded">
              <p className="font-bold">Recent Emails (7)</p>
              <p className="text-xs text-gray-500 italic">Syncing with Gmail API...</p>
            </div>
          </div>
        </div>

      </main>

      <footer className="fixed bottom-0 w-full p-4 bg-white border-t text-center text-xs text-gray-400">
        World-wide Multi-language Support (9) | Secured with AES-256 (10)
      </footer>
    </div>
  );
}
