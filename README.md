# Arora-Plywood-and-hardware-
Plywood and hardware business 
export default function AroraPlywoodWebsite() {
  return (
    <div className="min-h-screen bg-neutral-950 text-white font-sans">

      {/* Hero Section */}
      <section className="h-screen flex flex-col justify-center items-center text-center px-6 bg-gradient-to-br from-amber-900 via-neutral-900 to-black">
        <h1 className="text-5xl md:text-7xl font-bold text-amber-200">
          ARORA PLYWOOD & HARDWARE
        </h1>
        <p className="mt-3 text-xl text-neutral-300">
          ਅਰੋੜਾ ਪਲਾਈਵੁੱਡ & ਹਾਰਡਵੇਅਰ
        </p>
        <p className="mt-6 text-lg text-neutral-300 max-w-xl">
          Premium plywood, laminates & hardware solutions in Bathinda.
        </p>
        <p className="mt-4 text-amber-400 text-lg">
          ★★★★★ 4.9 Rating (21 Reviews)
        </p>
      </section>

      {/* About */}
      <section className="py-20 px-6 md:px-20 bg-neutral-900 grid md:grid-cols-2 gap-10">
        <div>
          <h2 className="text-4xl font-bold text-amber-300 mb-4">About Us</h2>
          <p className="text-neutral-300 text-lg">
            Arora Plywood & Hardware is a trusted supplier in Bathinda,
            known for quality materials and excellent customer service.
          </p>
        </div>

        <div className="bg-neutral-800 p-8 rounded-3xl">
          <h3 className="text-2xl text-amber-200 mb-4">Why Choose Us?</h3>
          <ul className="space-y-2 text-neutral-300">
            <li>✔ 4.9★ Customer Rating</li>
            <li>✔ Huge Variety of Hardware</li>
            <li>✔ Honest Pricing</li>
            <li>✔ Friendly Dealing</li>
          </ul>
        </div>
      </section>

      {/* Products */}
      <section className="py-20 px-6 md:px-20 bg-neutral-950">
        <h2 className="text-4xl text-center text-amber-300 mb-10">Products</h2>

        <div className="grid md:grid-cols-3 gap-6">
          {[
            "All Types of Plywood",
            "Laminates (Mica)",
            "Glass, Chimneys & Hardware"
          ].map((item, i) => (
            <div key={i} className="bg-neutral-900 p-6 rounded-2xl hover:scale-105 transition">
              <h3 className="text-xl text-amber-200">{item}</h3>
            </div>
          ))}
        </div>
      </section>

      {/* Contact */}
      <section className="py-20 px-6 md:px-20 bg-neutral-900 text-center">
        <h2 className="text-4xl text-amber-300 mb-6">Contact</h2>
        <p className="text-neutral-300">
          📍 Main Street No. 10, Near Gurudwara Sahib, Bathinda
        </p>
        <p className="text-neutral-300 mt-2">📞 085578 37035</p>
        <p className="text-neutral-300 mt-2">⏰ Open till 5:00 PM</p>
      </section>

      {/* Review */}
      <section className="py-20 px-6 md:px-20 bg-neutral-950">
        <h2 className="text-4xl text-center text-amber-300 mb-10">Reviews</h2>

        <div className="max-w-xl mx-auto bg-neutral-900 p-6 rounded-2xl">
          <p className="text-neutral-300 italic">
            "Very polite dealing with customers. A lot of variety in hardware like handles, hinges & mica."
          </p>
          <p className="mt-3 text-amber-400">— Sanjay Prem Margi</p>
        </div>
      </section>

      {/* Footer */}
      <footer className="py-6 bg-black text-center text-neutral-500 text-sm">
        © 2026 Arora Plywood & Hardware
      </footer>

    </div>
  );
}
