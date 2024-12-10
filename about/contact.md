<style>
    .hover-text {
        position: relative;
        display: inline-block;
        /*cursor: pointer;*/ /* Changes cursor to pointer on hover */
    }
    .hover-text img {
        display: none; /* Hide the image by default */
        position: absolute;
        top: 20px; /* Adjust position as needed */
        left: 0;
        width: 200px; /* Set the desired width */
        height: auto; /* Maintain aspect ratio */
        object-fit: cover;
        z-index: 1; /* Ensure the image appears above other content */
    }
    .hover-text:hover img {
        display: block; /* Show the image on hover */
    }
</style>

<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: #008CBA;
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}
</style>

<style>
        a:link {
            color: white; /* Unvisited link */
        }
        a:visited {
            color: white; /* Visited link */
        }
        a:hover {
            color: orange; /* Mouse over link */
        }
        a:active {
            color: red; /* Clicked link */
        }
    </style>

<center>

# Hearth


![Hearth Logo](./img/HearthLogo%20-%20PixelArt.png)

</center>