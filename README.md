import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input"; import { Textarea } from "@/components/ui/textarea";

export default function ZantechHome() { return ( <div className="p-4 space-y-6 max-w-3xl mx-auto"> {/* Header */} <header className="text-center"> <h1 className="text-4xl font-bold">Zantech Solutions</h1> <p className="text-lg text-gray-600">AI, Web & Tech Services Company</p> </header>

{/* Services Section */}
  <section>
    <h2 className="text-2xl font-semibold mb-2">Our Services</h2>
    <ul className="list-disc pl-6 text-gray-700">
      <li>AI/ML Project Solutions</li>
      <li>Web Development (Static & Dynamic)</li>
      <li>Python Automation Bots</li>
      <li>Resume & Portfolio Website</li>
    </ul>
  </section>

  {/* Join Us Form */}
  <section>
    <Card>
      <CardContent className="space-y-4 p-4">
        <h2 className="text-xl font-semibold">Join Our Team</h2>
        <Input placeholder="Your Name" />
        <Input placeholder="Your Email" type="email" />
        <Textarea placeholder="Tell us about your skills..." />
        <Button className="w-full">Apply Now</Button>
      </CardContent>
    </Card>
  </section>

  {/* Get Project Form */}
  <section>
    <Card>
      <CardContent className="space-y-4 p-4">
        <h2 className="text-xl font-semibold">Get Your Project Done</h2>
        <Input placeholder="Your Name" />
        <Input placeholder="Your Email" type="email" />
        <Textarea placeholder="Describe your project..." />
        <Button className="w-full">Submit Request</Button>
      </CardContent>
    </Card>
  </section>

  {/* Contact */}
  <footer className="text-center text-sm text-gray-500">
    Contact us at <a href="mailto:zantech@email.com" className="text-blue-600">zantech@email.com</a> or WhatsApp: <a href="https://wa.me/919999999999" className="text-green-600">Click Here</a>
  </footer>
</div>

); }
