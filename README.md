# Decison
Page Decision sh.p.k
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Phone, MapPin } from "lucide-react";

export default function HomePage() {
  return (
    <div className="min-h-screen bg-gray-100 text-gray-900">
      <header className="bg-blue-900 text-white p-6 text-center text-2xl font-bold">
        DECISION SH.P.K
      </header>
      
      <section className="container mx-auto p-8 text-center">
        <h2 className="text-3xl font-semibold mb-4">Rreth Nesh</h2>
        <p className="text-lg max-w-2xl mx-auto">
          Decision SH.P.K është një kompani e specializuar në ndërmjetësim të patundshmërive, këshillim për bizneset dhe marketing profesional.
        </p>
      </section>
      
      <section className="container mx-auto p-8">
        <h2 className="text-3xl font-semibold text-center mb-6">Shërbimet Tona</h2>
        <div className="grid md:grid-cols-3 gap-6">
          <Card>
            <CardContent className="p-6 text-center">
              <h3 className="text-xl font-semibold">Ndërmjetësim Patundshmërish</h3>
              <p>Ndihmojmë në shitjen dhe blerjen e pronave me transparencë dhe profesionalizëm.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6 text-center">
              <h3 className="text-xl font-semibold">Këshillim për Biznes</h3>
              <p>Ofrimi i strategjive efektive për rritjen dhe menaxhimin e bizneseve.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6 text-center">
              <h3 className="text-xl font-semibold">Marketing</h3>
              <p>Strategji dhe zgjidhje marketingu për të promovuar biznesin tuaj.</p>
            </CardContent>
          </Card>
        </div>
      </section>
      
      <section className="container mx-auto p-8 text-center">
        <h2 className="text-3xl font-semibold mb-4">Na Kontaktoni</h2>
        <div className="flex flex-col items-center space-y-4">
          <p><MapPin className="inline mr-2" /> Rruga B, 12, Prishtinë</p>
          <p><Phone className="inline mr-2" /> +383 48 661 006</p>
          <p><Mail className="inline mr-2" /> decision.gr@gmail.com</p>
          <Button className="mt-4" variant="primary">Dërgo Mesazh</Button>
        </div>
      </section>
      
      <footer className="bg-blue-900 text-white text-center p-4">
        &copy; 2025 Decision SH.P.K - Të gjitha të drejtat e rezervuara.
      </footer>
    </div>
  );
}
