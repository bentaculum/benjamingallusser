+++
# Display name
name = "Benjamin Gallusser"

# Username (this should match the folder name)
authors = ["admin"]

# Is this the primary user of the site?
superuser = true

# Role/position
role = "PhD student"

# Organizations/Affiliations
#   Separate multiple entries with a comma, using the form: `[ {name="Org1", url=""}, {name="Org2", url=""} ]`.
organizations = [ { name = "École Polytechnique Fédérale de Lausanne (EPFL)", url = "" } ]

# Short bio (displayed in user profile at end of posts)
bio = ""

# Enter email to display Gravatar (if Gravatar enabled in Config)
email = ""

# List (academic) interests or hobbies
#interests = [
#  "Machine Learning",
#  "Natural Language Understanding",
#  "Computer Vision",
#  "Artificial Intelligence"
#]

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups = []

# List qualifications (such as academic degrees)
[[education.courses]]
  course = "PhD student"
  institution = "École Polytechnique Fédérale de Lausanne"
  year = "2021-"

[[education.courses]]
  course = "Research Assistant and Software Engineer"
  institution = "Harvard Medical School"
  year = "2020"

[[education.courses]]
  course = "Visiting Student Researcher"
  institution = "Howard Hughes Medical Institute, Janelia Research Campus"
  year = "2019"

[[education.courses]]
  course = "M.Sc. in Computer Science"
  institution = "ETH Zürich"
  year = "2016-2019"

[[education.courses]]
  course = "B.Sc. in Informatics"
  institution = "Technical University of Munich"
  year = "2012-2016"

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/widgets/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.

[[social]]
  icon = "envelope"
  icon_pack = "fas"
  link = "mailto:benjamin.gallusser@protonmail.com"  # For a direct email link, use "mailto:test@example.org".

# Link to a PDF of your resume/CV from the About widget.
#  [[social]]
#   icon = "cv"
#   icon_pack = "ai"
#   link = "files/cv.pdf"

[[social]]
  icon = "twitter"
  icon_pack = "fab"
  link = "https://twitter.com/bengallusser"

[[social]]
  icon = "github"
  icon_pack = "fab"
  link = "https://github.com/bentaculum"

[[social]]
  icon = "google-scholar"
  icon_pack = "ai"
  link = "https://scholar.google.ch/citations?user=EIR1yVYAAAAJ&hl=en"

[[social]]
    icon = "linkedin"
    icon_pack = "fab"
    link = "https://www.linkedin.com/in/bengallusser"

+++
### Short bio 
I am currently a PhD student in [Martin Weigert's group](https://www.epfl.ch/labs/weigert-lab/) at EPFL in Switzerland, where I develop machine-learning based methods for analysing microscopy images of the building blocks of life.
Proteins, organelles, cells, tissues or even entire animals; to learn about them we can often simply take a (sophisticated) picture or video. And after that we need to extract quantitative information from our recordings!
While supervised deep learning is enjoying a lot of success for processing bioimages, it is often limited by a lack of appropriate ground truth annotations. How can we incorporate uncurated images that come fresh off the microscope into training neural networks?

If you are excited about this as well please reach out :)


Previously, I have worked on automating cell organelle segmentation in electron microscopy data in [Tom Kirchhausen's lab](https://kirchhausen.hms.harvard.edu) at Harvard Medical School, as well as on [3D neuron reconstruction](https://github.com/benjamin9555/project_summaries/blob/master/msc_thesis_learning_to_agglomerate_in_region_adjacency_graphs.pdf) from electron microscopy in [Jan Funke's group](https://www.janelia.org/lab/funke-lab/).
