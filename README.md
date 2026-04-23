
export default function SistersBeautyParlourWebsite() {
  return (
    <div className="min-h-screen bg-pink-50 text-gray-800 font-sans">
      {/* Hero Section */}
      <section className="bg-white shadow-sm">
        <div className="max-w-6xl mx-auto px-6 py-16 text-center">
          <h1 className="text-4xl md:text-6xl font-bold text-pink-700">
            Sister’s Beauty Parlour & Bridal Studio
          </h1>
          <p className="mt-4 text-lg md:text-xl text-gray-600">
            Beauty • Bridal • Glow • Care
          </p>
          <p className="mt-6 text-base md:text-lg">
            Sikandar Pur Kundal, Near Marine Drive
          </p>
          <p className="mt-2 text-base md:text-lg font-medium">
            Call / WhatsApp: 6207314571
          </p>
          <div className="mt-8 inline-block bg-pink-100 text-pink-800 px-6 py-3 rounded-2xl font-semibold shadow">
            🎓 Special Offer: Students Get 50% OFF
          </div>
        </div>
      </section>

      {/* Services */}
      <section className="max-w-6xl mx-auto px-6 py-14">
        <h2 className="text-3xl font-bold text-center text-pink-700">
          Our Services
        </h2>
        <div className="grid md:grid-cols-3 gap-6 mt-10">
          {[
            "Facial",
            "Cleanup",
            "Detan",
            "Mehendi",
            "Waxing",
            "Manicure",
            "Pedicure",
            "Bridal Makeup",
            "Skin Care"
          ].map((service) => (
            <div
              key={service}
              className="bg-white rounded-2xl shadow p-6 text-center hover:shadow-lg transition"
            >
              <p className="text-lg font-medium">{service}</p>
            </div>
          ))}
        </div>
      </section>

      {/* Timing */}
      <section className="bg-white py-14">
        <div className="max-w-4xl mx-auto px-6 text-center">
          <h2 className="text-3xl font-bold text-pink-700">About Us</h2>
          <p className="mt-6 text-lg max-w-2xl mx-auto">At Sister’s Beauty Parlour & Bridal Studio, we believe every woman deserves to look beautiful and feel confident. We use quality products and modern beauty techniques to bring out the best in you.</p>
          <p className="mt-4 text-gray-600">Your beauty is our passion.</p>
        </div>
      </section>

      {/* Contact */}
      <section className="max-w-5xl mx-auto px-6 py-16 text-center">
        <h2 className="text-3xl font-bold text-pink-700">Contact Us</h2>
        <p className="mt-4 text-lg">Sikandar Pur Kundal, Near Marine Drive</p>
        <p className="mt-2 text-lg font-medium">Phone: 6207314571</p>
        <a
          href="tel:6207314571"
          className="inline-block mt-8 bg-pink-600 text-white px-8 py-3 rounded-2xl shadow hover:bg-pink-700 transition"
        >
          Call / WhatsApp Now
        </a>
      </section>

      {/* Footer */}
      <footer className="bg-pink-700 text-white text-center py-6">
        <p>© 2026 Sister’s Beauty Parlour & Bridal Studio. All rights reserved.</p>
      </footer>
    </div>
  );
}
